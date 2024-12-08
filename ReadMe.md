## Deepfake Detection Project using CNN-LSTM Architecture

This project is a deepfake detection model developed using a CNN-LSTM architecture. The dataset used is the DFDC 
(Deepfake Detection Challenge) dataset, which is available on Kaggle. The model is implemented in a Jupyter Notebook 
(.ipynb), which you can execute either locally or on a cloud-based platform like Google Colab.

## Requirements
    Python 3.x
    Jupyter Notebook or any IDE that supports .ipynb (like Google Colab or Kaggle)
    Kaggle account (to download the dataset)
    Required libraries:
    PyTorch
    Torchvision
    Pandas
    NumPy
    OpenCV
    Matplotlib
    Scikit-learn

## Installation Steps locally(VS code)
    1. Set up Python environment:
        Install Python if not already installed. Download it from Python's official site.
        Set up a virtual environment:
            python -m venv venv
            
    2. Activate the virtual environment:
        Windows:
            venv\Scripts\activate.bat
        
        macOS/Linux:
            source venv/bin/activate

    3. Install required packages:
        Install the required libraries:
            pip install torch torchvision pandas numpy opencv-python matplotlib scikit-learn

    4. Download the DFDC dataset:
        Download the DFDC dataset using the Kaggle API(if exists) otherwise manually download it to your local environment:
            kaggle datasets download -d deepfake-detection-challenge

        Unzip the dataset:
            unzip deepfake-detection-challenge.zip

    5. Run the Jupyter Notebook
        Start Jupyter Notebook:
            Open the .ipynb file in your VS Code.

        Start running each cells after fixing the location of the files or folders used.      

## Installation Steps (on Kaggle)
    1. Create a Kaggle account:
        If you do not have a Kaggle account, sign up at Kaggle.

    2. Add the dataset:
        In your Kaggle Notebook, go to the Data section and add the Deepfake Detection Challenge (DFDC) dataset as an Input.
        You can search for the dataset and directly attach it from Kaggle’s dataset repository.

    3. Open the Jupyter Notebook:
        Upload the .ipynb file to your Kaggle environment or start a new Kaggle Notebook and copy the code from the original notebook.
    
    4. Adjust file paths:
        Update the file paths to match the location of the dataset in the Kaggle environment.

    5. Execute the notebook:
        Run the notebook by executing all the cells step by step.

## Running on Google Colab
    1. Set up the environment:
        Open Google Colab and upload the .ipynb file.

        Install required libraries(if required):
            Use the following cell to install missing libraries in Colab:
                !pip install torch torchvision pandas numpy opencv-python matplotlib scikit-learn
    
    2. Download the dataset:
        Download the DFDC dataset manually from Kaggle and upload it to your Google Drive or download using the Kaggle API.
        
        Run the notebook:
            Adjust paths if required and run all cells.