# ResNet
We have transfer learning to retrain the final 10 layers in the ResNet model.
Using the celeb_deepfake version2 dataset.
Transfer Learning: Having the preordained model which is ResNet trained on Image net data. 
We have freeze the initial 130 layers and made the rest of the layer trainable on the deepfake dataset.
Test accuracy of 92.424%. 

![2022-12-20 (1)](https://user-images.githubusercontent.com/90169754/208796410-0c943e75-59d9-490e-b6f5-24df73739317.png)
