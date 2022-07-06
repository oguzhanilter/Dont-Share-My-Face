# Dont-Share-My-Face
Privacy Preserving Inpainting for Visual Localization. The paper of the project was accepted to [International Conference on Intelligent Robots and Systems (IROS) 2022](https://iros2022.org/).

# Authors
Saad Himmi*, Oguzhan Ilter*, François Pailleau, Roland Siegwart, Berta Bescos^, Cesar Cadena^

*Contributed equally to this work. 
^Supervised equally this project.


# Abstract 
Visual localization is an important task for many robotic and augmented reality applications. As localizing within large scale maps can be memory and computationally demanding, cloud-based localization services are appealing for developers. However, such services raise important privacy concerns for both passive and active users. In particular, some sensitive information might be revealed by an attacker who intercepts data during the data-sharing process. Therefore, the sensitive data in the image should be concealed before it is shared. As a motivating case, we demonstrated the exposure generated by the common feature descriptor SIFT when attempting to recover private content. In this paper, we propose a pipeline to effectively conceal privacy-sensitive
image regions from possible attacks to the transmission or localization services, by making use of learning-based image inpainting techniques while preserving, and even boosting, the localization performance. We tested our pipeline with two off-the-shelf localization services based on deep neural networks on the publicly available Oxford Robotcar dataset, showing that the localization performance on our generated private concealed images is on par with the non-private baseline.

# Availability 
The source code will be made publicly available as soon as the paper is published in [IROS 2022](https://iros2022.org/).


