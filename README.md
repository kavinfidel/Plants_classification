# Plants_classification

The following rep contains files that pertain to image classification using CNNs
Dataset used: Ornamental Plants (https://drive.google.com/file/d/1sML4-U5K6fNo28YjsKz3gUvsMeZ0Aus7/view)

The Ipynb(Notebooks) folder contains all the ipynb files.
Models folder contains the compiled transfer learning and fine tuned models.
Fine tuned models are in a subfolder called Fine_Tuned
The file also  contains the Ornamentals dataset.

Types of Plants: 
1. Damask Rose
2. Echeveria Flower
3. Mirabillis Jalapa
4. Rain Lily
5. Zinnia Elegans
6. 
The images are used to train on the following pretrained CNN models using Transfer Learning
and Fine-Tuning:

1. Model-1: InceptionResNetV2
2. Model-2: EfficientNetV2B0
3. Model-3: ConvNeXtTiny

Furthermore, and ensemble model is generated using the prediction results of the 
best performing Fine-Tuned models.
