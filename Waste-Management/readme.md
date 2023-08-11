# Deep Learning Model with Multi-Object Detection for Recyclable Waste Management
<img width="612" alt="image" src="https://github.com/priyasjsu/Computer-Vision-projects/assets/113324576/98fc0aca-7582-432f-abc7-169f47b5ae2e">

# Project Introduction 
The rapid growth of the global population, urbanization, and improved living standards has led to a pressing issue: waste management. Predictions indicate that annual waste production will spike to 3.40 billion tons by 2050, from the current 2.01 billion tons. Mismanaged waste poses severe consequences, including ocean pollution, disease transmission, harm to wildlife, and economic setbacks. Urgent action is needed to address this issue stemming from decades of inadequate waste management due to population and economic growth.
Waste management, in addition to being an urgent global concern, is also a costly one. In fact, it can form the single largest budget item for many municipalities. In low-income countries, waste management takes up, on average, as much as 20% of municipal budgets.
Often administered by local authorities with limited resources and limited ability to plan, execute, and monitor, waste management, especially sustainable waste management, can be an elusive goal for underdeveloped and underfunded municipalities. As a result, the dire impacts of poor waste management tend to fall most heavily on the poor, who often live in underserved areas and have little control over the waste being disposed of legally or illegally near their homes. Recycling—the process of repurposing and reusing trash—is arguably one of the most effective mechanisms for reducing waste and improving waste management. In fact, recycling is considered a fundamental pillar of a sustainable, circular economy. Recycling is a multi-step process that involves the collection then sorting and categorization of post-consumer material. The process currently requires manual hand-sorting of trash by both consumers as well as waste management employees before the trash is fed to filters that filter out more defined objects based on specific properties such as thickness, color, and use.

## Objective
project motivation is to develop a recyclables classification and quantification application that could be utilized by households and waste management centres alike to categorize types of recyclable waste and forecast waste quantity. 
To address this issue, we are leveraging cutting-edge advances in deep learning, computer vision, and other technologies.

The proposed application must meet the following requirements: detect the waste recyclable object or objects within an image; correctly classify them as plastic, glass, paper or metal recyclable categories in real-time. As the datasets in the research used are open-source, no clearance or authentication is required.

## YOLOv5 Object Detection Model- 
<img width="624" alt="image" src="https://github.com/priyasjsu/Computer-Vision-projects/assets/113324576/df9bf891-1b3a-4aef-a4d4-5d34515e2167">

YOLOv5 is a single-stage object detection algorithm that works in a grid system. An image is divided into a grid system, then each cell within the grid detects any objects it contains, as shown in Figure. YOLOv5 uses a convolutional neural network algorithm to identify and locate target objects within images. As previously mentioned, a single convolutional network determines both bounding boxes and class probabilities simultaneously in YOLOv5. As a result, this algorithm has proven to be much faster than other object detection algorithms.

## Project Approaches and Methods
The approach in this project involves data collection, data preprocessing, image processing, model training (here YOLO v5), model testing, and model evaluation can be seen in the given data flow.

<img width="468" alt="image" src="https://github.com/priyasjsu/Computer-Vision-projects/assets/113324576/b54af6d2-3f42-4954-9996-5ee9ca5acf41">

## Dataset
Training data for this project requires a collection of images of recyclable and non-recyclable objects. The model is trained with images from these datasets. A pre-calculated portion of these images is used for the testing/validating dataset in addition to some real-time images and collaged images for the purpose of multi-class object detection. this implementation used TrashNet and Trashbox datasets to train model.

<img width="624" alt="image" src="https://github.com/priyasjsu/Computer-Vision-projects/assets/113324576/f24e10bb-67ad-4667-a28f-eb3a0f17d63c">

### Dataset Preparation using Roboflow
Roboflow is a computer vision platform that helps developers build and deploy machine learning models for tasks like object detection, image segmentation, and more. It provides tools to preprocess and augment image data, and annotation objects in images.
This project used Roboflow to prepare the data for training the model such as balancing the data, Annotating objects, and augmentation.

<img width="364" alt="image" src="https://github.com/priyasjsu/Computer-Vision-projects/assets/113324576/42320d5b-2b69-4c4b-a824-d1921e2382f5">

#### Annotation and balance dataset
<img width="642" alt="image" src="https://github.com/priyasjsu/Computer-Vision-projects/assets/113324576/fbc2a6ae-cff6-4e52-8d38-99e4816b04d7">
<img width="637" alt="image" src="https://github.com/priyasjsu/Computer-Vision-projects/assets/113324576/b7e83b62-a168-4e83-958b-4f8512e79f53">

### Result
<img width="624" alt="image" src="https://github.com/priyasjsu/Computer-Vision-projects/assets/113324576/0d6e34f1-42fe-4a50-9795-fca9e96efca5">

[Click here to see the full documentation of the model and result metrics](https://github.com/priyasjsu/Computer-Vision-projects/blob/main/Waste-Management/docs/waste-management-Yolo-v5-report.pdf)














