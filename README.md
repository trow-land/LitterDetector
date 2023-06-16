# Litter Detector
This project started me on my machine learning and computer vision journey. This served as my foundation of knowledge of computer although a challenging project, it highlighted both the strengths and weaknesses of using computer vision for a system as varied as this. 

This repository contains my work on leveraging machine learning models for detecting litter in a variety of contexts.

## Challenges

One of the primary challenges we faced during the Litter Detection project was the immense variability within each category of litter. From packaging materials to food waste, each type of litter exhibits a different size, color, texture, and shape within that class. This diversity proved as significant challenge when implementing a detection and categorisation system, espessially if the sysem was to detect a wide variety of litter categories.

Additionally, data scarcity posed a significant challenge. In order to train a machine learning model effectively, a substantial amount of high-quality, varied data is required. This data should ideally cover the full range of litter types that the model will encounter in real-world scenarios. However, obtaining such a comprehensive dataset for litter was not easy, limiting our ability to fine-tune the model to ensure accurate and reliable litter detection. 

These challenges underlined the complexities involved in using computer vision for litter detection, and provided valuable insights that shaped the development process.

## Inference Examples
For examples of the project's results, please refer to the [images](https://github.com/trow-land/LitterDetector/tree/main/images) folder where you'll find examples of the models' inference outputs.

## Dataset
For the purpose of this project, I utilised the Trash Annotated in Context (TACO) dataset. You can learn more about it on its [official website](http://tacodataset.org/), [Github repository](https://github.com/pedropro/TACO), or read about it in this [research paper](https://arxiv.org/abs/2003.06975). 

I eventually made substantial modifications to the dataset used for the university part of this project. It was augmented with additional images from the unofficial set, my own images and narrowed down to concentrate on a few key classes of litter.

## Repository Contents

### Litter Detection with YOLOv5
This explore the use of the You Only Look Once version 5 (YOLOv5) algorithm for real-time object detection. This noteook includes the implementation details and results. -> Soon to be updated to more current version

### Litter Detection and Instance Segmentation with Detectron2 Mask R-CNN
A short introduction into a more advanced approach to litter detection by implementing the Mask R-CNN model through the Detectron2 library. This model not only detects the litter but also performs instance segmentation to precisely locate each item within the image.

### Litter Detection with Computer Vision (Undergraduate Dissertation Thesis)
This section contains my undergraduate dissertation on litter detection using deep learning computer vision techniques. It offers a detailed introduction into computer vision theory and how it can be applied to a real-world problem.

## Acknowledgments
- Cardiff University
- Supercomputing Wales
- Dr Yulia Hicks (Supervisor)

![example](https://github.com/trow-land/LitterDetector/blob/main/images/taco_detectron3.png)


## Get in Touch

I am currently seeking opportunities as a Computer Vision Engineer within the UK. I hope the projects shared in this repository clearly demonstrate my dedication and enthusiasm for Computer Vision, particularly in the context of Agri-Tech and environmental sustainability. I am excited to put this enthusiasm to use in a role where I can make a positive impact on agriculture, environment, and beyond.

Apart from professional opportunities, I'm always open to collaborating on interesting projects or discussions in the field of Computer Vision. If you'd like to connect, offer advice on improving my projects, or discuss potential collaboration, please feel free to reach out.

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/thomas-rowland-07a785155/) or email at [tom_rowland@outlook.com](mailto:tom_rowland@outlook.com). 

