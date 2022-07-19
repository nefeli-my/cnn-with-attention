## CNN embedded with attention mechanisms for Alzheimer's disease classification 

This project was created for the purposes of the [e-Health and m-Health Technologies](https://www.biosim.ntua.gr/en/course/10) course at [ECE NTUA](https://www.ece.ntua.gr/en), along with Fotis Pericharos, Dimitris Poulios and Nikiforos Tsoulias. 

### Overview
For this project, a simple convolutional neural network was developed for tackling the multi-class classification problem presented with the [Kaggle Alzheimer's Dataset](https://www.kaggle.com/datasets/tourist55/alzheimers-dataset-4-class-of-images). The initial model was enhanced using two different attention mechanisms ([ECA-NET](https://blog.paperspace.com/attention-mechanisms-in-computer-vision-ecanet/) [1] and [CBAM](https://github.com/kobiso/CBAM-keras/blob/master/models/attention_module.py) [2]), thus resulting in two new classification models. For comparison purposes, all of the three architectures were later on evaluated using standard metrics (accuracy, precision, recall and AUC), while the [Grad-CAM](https://pyimagesearch.com/2020/03/09/grad-cam-visualize-class-activation-maps-with-keras-tensorflow-and-deep-learning/) [3] technique was used as a visualization tool. 

### References 

[1] Wang Q., Wu B., Zhu P., Li P., Zuo W. and Hu Q. ECA-Net: Efficient Channel Attention for Deep Convolutional Neural Networks. IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR). (2020). https://doi.org/10.1109/CVPR42600.2020.01155

[2] Woo S., Park J., Lee JY., Kweon I.S. CBAM: Convolutional Block Attention Module. Computer Vision – ECCV 2018. Lecture Notes in Computer Science(), vol 11211. Springer, Cham. (2018). https://doi.org/10.1007/978-3-030-01234-2_1

[3] Selvaraju, R.R., Cogswell, M., Das, A. et al. Grad-CAM: Visual Explanations from Deep Networks via Gradient-Based Localization. Int J Comput Vis 128, 336–359. (2020). https://doi.org/10.1007/s11263-019-01228-7
