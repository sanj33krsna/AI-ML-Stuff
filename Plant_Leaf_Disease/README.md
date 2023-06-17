# Plant Leaf Disease Classification - Using ResNet

Tools Used: TensorFlow, Jupyter 

## Why ResNet:

ResNet for this time. The difference between normal Neural Networks and Residual Networks is the addition of **Identity-Skip-Connection**. What happens in Neural Networks is that there is a lot of layers and our process is passed through this layer and we obtain some useful information, however this could also lead to **Vanishing Gradient Problem** which is caused due to over-complexity inside the layer. To avoid this problem we use the skip & using this skip doesn't lose any information and passing this to another connection we could possible infer what the complexity in the previous layers were. Here's a simple residual block:

<p> <img src="https://github.com/sanj33krsna/AI-ML-Stuff/blob/main/Plant_Leaf_Disease/ResNet.png" width="600"> </p>

## Output:

<p> <img src="https://github.com/sanj33krsna/AI-ML-Stuff/blob/main/Plant_Leaf_Disease/Screenshot%20from%202023-06-17%2021-11-06.png" width="600"> </p>
