# DeepRay 🦠
![logo](https://user-images.githubusercontent.com/46050829/200048325-230a5f61-4c25-4c29-ba88-dab39e864168.png)
# Introduction
DeepRay is an implementation of medical image Semantic Segmentation using a U-Net architecture. It can detect the infected areas in a COVID-19 patient's chest X-ray image. 

I used the <a href="http://qatacov.live/" target="_blank">Qata-COV19</a> dataset. The researchers of Qatar University and Tampere University have compiled the QaTa-COV19 dataset that consists of 9258 COVID-19 chest X-ray images.

The U-Net architecture can classify an image down to pixel-level, i.e. Semantic Segmentation. This capability is mainly because of the *transposed convolution* operator which can up-sample the learned features back to the input's dimension. Here's the architecture:
<p align="center">
  <img src="https://user-images.githubusercontent.com/46050829/200048878-be0a4a0c-e5f1-4281-9d01-8473e2f468a7.png" width="70%"/>
</p>

# Links
- <a href="https://colab.research.google.com/drive/12XqE7OnsepLl5436N46dkIGC7YpURdLt?usp=share_link" target="_blank">DeepRay on Google Colab</a>

You may also download the notebook from this repository.

# Contact
If there are any questions or recommendations, you can reach out to me at <a href="mailto:itsrezamansouri@gmail.com" target="_blank">itsrezamansouri@gmail.com</a> or <a href="mailto:std_reza_mansouri@khu.ac.ir" target="_blank">std_reza_mansouri@khu.ac.ir</a>.
