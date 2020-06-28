# dental-landmark-detection
estimation of dental arch in maxillary deformities by CNN on CBCT images
With the increasing usage of MSCT images as a most common medical imaging system for diagnosis, treatment planning, and clinical studies, it is increasingly becoming a vital factor to use machine learning-based systems to provide reliable information for surgical pre-planning. Segmentation of tooth in cone-beam CT images is a critical preprocessing step for some applications such as computer-aided diagnosis and deformity detection. In this paper, we propose a fast and automatic method to effectively distinguish individual teeth from the sockets of teeth in dental cone-beam CT images. we have designed a convolutional neural network by Keras in TensorFlow. The dataset encompasses 720 axial slice dental images from 120 subjects as training and validation. As this number is not enough for training the neural networks we used other slices of the subject and data augmentation to improve the network. The anatomical landmarks corresponding to individual teeth are manually detected in 3D Slicer. Our method was validated by test dataset of dental CT scans, and the results were compared with the manually segmented result and conventional methods. The average error of absolute value was 3.48% ± 0.91%, which was more accurate than conventional methods. The proposed method identified the individual teeth accurately, demonstrating that it can give dentists substantial assistance during dental surgery. 
