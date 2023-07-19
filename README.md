# Medical Diagnostics App: 👩‍⚕️🔬 End-to-End Precise White Blood Cell Segmentation

![Medical Diagnostics App](https://github.com/pvashish/End_to_End_Cell_Segmentation_YOLOV8/blob/main/Capture.PNG)

## Project Overview 🚀

The Medical Diagnostics App is a cutting-edge project focused on precise white blood cell segmentation, significantly improving medical diagnostics. Leveraging skills in AWS SageMaker ☁️, Computer Vision 👁️‍🗨️, MLOps ⚙️, YOLOv8 🎯, Azure ☁️, Docker 🐳, CI/CD development 🔄, GitHub Actions 🤖, and Flask 🌐, this app aims to revolutionize medical image analysis and enhance prompt patient care.

## Key Achievements 🏆

- **YOLOv8-based Segmentation**: Developed an advanced YOLOv8-based app for precise 'white blood cell' segmentation. This breakthrough technology overcomes variations in cell appearances and sizes, ensuring accurate diagnostics in medical imaging. 🎯🔬🩸

- **Streamlined Segmentation Pipeline**: Streamlined the white blood cell segmentation pipeline using Amazon SageMaker and an S3 bucket. This optimization enhances the efficiency of medical image analysis and empowers healthcare professionals to make prompt and accurate patient care decisions. ⚙️☁️💻

## How to Use 📝🔧

To use the Medical Diagnostics App for white blood cell segmentation, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine using the following command:



# End-to-end-Cell-Segmentation-Using-Yolo-v8

## Workflows

1. constants
2. entity
3. components
4. pipelines
5. app.py


# How to run?
### STEPS:

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n cell python=3.11 -y
```

```bash
conda activate cell
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```


# AZURE-CICD-Deployment-with-Github-Actions

## Save pass:

XXXXXXXXXXXXXXXXXXXX


## Run from terminal:

docker build -t xxx.xxxxx.x/cell:latest .

docker login xxx.xxxxx.x

docker push xxx.xxxxx.x/cell:latest


## Deployment Steps:

1. Build the Docker image of the Source Code
2. Push the Docker image to Container Registry
3. Launch the Web App Server in Azure 
4. Pull the Docker image from the container registry to Web App server and run 
