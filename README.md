# FoodDetection
MBA thesis: Food detection using YOLOv8 and Nutritional Info Extraction using Selenium

## Abstract:
In this study, Artificial Intelligence and Computer Vision were used to create a nutritional awareness tool, motivated by the increase in obesity and diabetes in Brazil and worldwide. Two architectures of the Python language were used for this purpose, Detectron2 (Facebook) and YOLOv8 (Ultralytics). From pre-trained models of both architectures, a dataset containing 4900 images for fine-tuning training and 1600 images for validation was used to identify and segment food on a plate. Furthermore, an additional step of performance evaluation using disturbances in the contrast and brightness of the images was done in order to verify the robustness of the results in adverse lighting conditions. The YOLOv8s architecture showed the best performance in object detection and instance segmentation, with high recall and instance separation (mAP50 and mAP50-95). After choosing the best model, the step of acquiring nutritional information was added using the technique of scraping (Selenium architecture), incorporating a summary of this information into the segmented image - like amount of Protein, which Vitamins and Minerals are present etc. The tool proved to be promising to help users choose healthier foods and the use of artificial intelligence and computer vision was effective in identifying and segmenting foods. It is suggested to expand the study to include the estimation of food volume and the calculation of the Glycemic Index, as well as to increase the variety of types of preparation of the analyzed foods.

Dataset from Roboflow, link below (all credits to the author Lawrence Hair):
<https://universe.roboflow.com/lawrence-hair-wpavf/food-v18>


