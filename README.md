# ASSESSMENT-OF-STRESS-INDUCED-ARRHYTHMIA-THROUGH-ECG-SIGNAL-ANALYSIS-

 
Stress is a major contributor to cardiovascular disorders, frequently causing arrhythmia that is not seen 
until they are well advanced. This study introduces a deep learning-based method for using electrocar
diogram (ECG) information to identify stress-induced arrhythmias. The suggested model combines 
Long Short-Term Memory (LSTM) networks to capture temporal dynamics in ECG data with Convo
lutional Neural Networks (CNNs) for the extraction of spatial features. To increase signal clarity, ECG 
data are pre-processed using wavelet denoising and segmentation. Publicly accessible datasets, such as 
the MIT-BIH Arrhythmia and MIT-BIH Noise Stress Test Databases, are used to train and assess the 
model.  
TensorFlow Lite is used to improve the learned model for real-time inference on edge devices like the 
Raspberry Pi and NVIDIA Jetson Nano for practical deployment. According to experimental data, the 
F1- score is 94.07%, the classification accuracy is 94.06%, and the precision is 94.08%. Because of its 
short inference latency and low resource use, the system may be integrated into portable ECG moni
toring devices. By identifying stress-related arrhythmic events, this study advances the development of 
sophisticated, real-time heart health monitoring systems that facilitate remote healthcare applications 
and early intervention. 
