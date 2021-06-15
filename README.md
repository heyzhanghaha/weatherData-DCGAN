# MDCGAN
This is the code used in the paper titled MDCGAN: Desensitized Meteorology Data Generation Model Based on Deep Convolutional Generative Adversarial Network

## Paper link

## Abstract
Artificial intelligence (AI) profoundly affects the research of meteorology. As an AI method, deep learning greatly improves the accuracy of weather forecasting. Deep learning training requires a lot of data, while the collection of meteorological data faces some problems, such as the long collection cycle, the high cost, and the desensitization requirement. In this paper, a deep learning model named MDCGAN (Meteorology Deep Convolutional Generative Adversarial Network) is proposed, which can generate the virtual meteorological data with the similar statistical characteristics to the real meteorological data, and the generated meteorological data can be used for the deep learning-based data analysis, weather forecasting, historical weather reproduction and other researches. The data generated by the MDCGAN model meets the requirements of data augmentation and data desensitization at the same time. In this paper, the meteorological data set of Kennedy Airport published by NOAA (National Oceanic and Atmospheric Administration) was used for the experiments of the MDCGAN model. The reliability and validity of generated meteorological data were analyzed and tested. The comparison between the generated data and the real data shows that they have the similar statistical characteristics and can achieve the same effect in the time series prediction. Experimental results show that the MDCGAN model can effectively solve the data augmentation and desensitization problems. The MDCGAN model provides a convenient tool for the meteorology researches based on deep learning, which can automatically generate a large amount of safe and reliable data, especially suitable for the meteorology researches with small sample data.

## Model Structure of MDCGAN
![1](https://user-images.githubusercontent.com/58810217/117533276-83b33780-b01e-11eb-86fb-9361eda2ed2b.jpg)

## Usage

Use parameter2.pkl in the model file to generate weather data
