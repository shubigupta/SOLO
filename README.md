# Segmenting Objects by Location PyTorch Implementation

The project involved the implementation of the instance segmentation algorithm defined in paper: [SOLO](https://arxiv.org/abs/1912.04488). The main idea behind the paper is that different instance categories can be differentiated by their location and size in an image. The image is divided into SxS grids. Each grid cell is responsible for locating the instance's center which falls in the pixels it corresponds to in the original image. Size is handled by detecting at different levels of Feature Pyramid Network.

## Results
[comment]: ![](./Results/1.png)     ![](./Results/1_mask.png)
![](./Results/2.png)     ![](./Results/2_mask.png)
![](./Results/3.png)     ![](./Results/3_mask.png)

<p float="left">
  <img src="./Results/1.png" width = 40%/>
  <img src="./Results/1_mask.png" width = 40%/> 
</p>
<p float="left">
  <img src="./Results/2.png" width = 40%/>
  <img src="./Results/2_mask.png" width = 40%/> 
</p>
<p float="left">
  <img src="./Results/3.png" width = 40%/>
  <img src="./Results/3_mask.png" width = 40%/> 
</p>