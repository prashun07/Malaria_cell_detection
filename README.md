# Malaria_cell_Images_dataset
The dataset contains 2 folders

Infected
Uninfected
And a total of 27,558 images.
Dataset download link:https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria

ResNet9 model is used to classify and detect the images of cell.
we have to tell either the cell in parasitized or uninfected.
steps:
1.Download dataset from kaggle.
2.Explore and remove trash.
3.Load data set using imageFolder.
4.Load data into Gpu.
5.prepare nueral network(resnet 9).
6.Train the model.
7.Test the accuracy and validation loss.

Whole Data preprocessing and nueral network is prepared by using Pytorch.


![grid_of_cell](https://user-images.githubusercontent.com/54842624/104820328-135b8d00-585a-11eb-8687-ad91b735de7d.png)

![Parasitized_cell](https://user-images.githubusercontent.com/54842624/104820359-46058580-585a-11eb-9475-d1035180da59.png)

![uninfected_cell](https://user-images.githubusercontent.com/54842624/104820376-5158b100-585a-11eb-81a6-8b2498b172d8.png)
