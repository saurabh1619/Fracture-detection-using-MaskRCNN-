# Fracture-detection-using-MaskRCNN-

Deep learning solutions have immense capability to solve medical problems. One of main constraint, while addressing a medical problem through deep learning, is the lack of data availability . To address this issue, i tried to gather images of forearm bone fracture radio graphs, a custom dataset consisting of images from a simple google search and Mura ( a large X ray dataset) is prepared. 

With this dataset i aimed to solve the problem of bone fracture detection and segmentation, i prepared a script utilizing the prowess object detection through MaskRCNN model. I utilized its pre-trained weights from COCO dataset, and further trained the model (excluding a few layers) on my custom dataset. Training the model with the data of just 60 images, and for only 7 epochs, showed some astonishing results. The model was successfully able to detect and score the ROI (region of interest) for detected fracture as seen in the video. Concluding, that the present gen deep learning solutions have the capabilities to address the medical industry's problems even with the data constraint.

Annotator: http://www.robots.ox.ac.uk/~vgg/software/via/
MaskRCNN : https://github.com/matterport/Mask_RCNN
Mura dataset : https://stanfordmlgroup.github.io/competitions/mura/
