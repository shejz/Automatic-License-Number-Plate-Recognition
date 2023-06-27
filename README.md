# Automatic License / Number Plate Recognition

NOTEBOOK DEMO:  [![Nbviewer](https://github.com/jupyter/design/blob/main/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/shejz/Automatic-License-Number-Plate-Recognition/blob/main/opencv_anpr.ipynb)

**Automatic License/Number Plate Recognition (ANPR/ALPR) is a process involving the following steps**:
1. Detect and localize a license plate in an input image/frame
2. Extract the characters from the license plate
3. Apply some form of Optical Character Recognition (OCR) to recognize the extracted characters

ANPR tends to be an extremely challenging subfield of computer vision, due to the vast diversity and assortment of license plate types across states and countries.

- ANPR performed in controlled lighting conditions with predictable license plate types can use basic image processing techniques.
- More advanced ANPR systems utilize dedicated object detectors, such as **HOG + Linear SVM**, **Faster R-CNN**, **SSDs**, and **YOLO**, to localize license plates in images.
- State-of-the-art ANPR software utilizes **Recurrent Neural Networks (RNNs)** and **Long Short-Term Memory networks (LSTMs)** to aid in better OCR’ing of the text from the license plates themselves. And even more advanced ANPR systems use specialized neural network architectures to pre-process and clean images before they are OCR’d, thereby improving ANPR accuracy.


**License plate recognition systems are further complicated by**:

- Dynamic lighting conditions including reflections, shadows, and blurring
- Fast-moving vehicles
- Obstructions

**Additionally, large and robust ANPR datasets for training/testing are difficult to obtain due to**:

- These datasets containing sensitive, personal information, including time and location of a vehicle and its driver
- ANPR companies and government entities closely guarding these datasets as proprietary information

## Results

![](https://github.com/shejz/Automatic-License-Number-Plate-Recognition/blob/main/Results.jpg)



