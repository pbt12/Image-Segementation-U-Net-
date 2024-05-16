# Image-Segementation U-Net Architecture

(This work is originally intended to study the mechanical failure by tensile stress after tensile testing. We thought to prepare samples, perform tensile testing till their breaking point, and then use Image segmentation using fully convolutional layers (U-Net) to identify the crack areas. This is important aspect while inspecting materials in aerodynamic industry, this might add an additional layer of confirmation for no-crack check. But because of lack of samples, we were not able to get sufficient training data till the last. So, we used our learnings to segment brain tumours from images using the same U-Net architecture.)


<p align="center">
	<img src = 'https://github.com/pbt12/Image-Segementation-U-Net-/assets/74967927/11efb77f-5de1-4b4d-ae6b-55958409dbcc'/>
	<br/>
	Obtained results from our work
</p>



I have used brain-tumor segment dataset which is available on the internet. You can run 'download_data.sh' shell script to download all data. It contains 3064 MRI images and 3064 masks. After that run the following command to convert data in useable form. 

``` python tumor-segmentation-unet/mat_to_numpy.py brain_tumor_dataset/ ```

Once the data is ready, we can run the 'brain_tumour_segmentation.ipynb' file, which uses a U-Net architecture, a fully convoluted Neural Network with novel architecture.




