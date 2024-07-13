# text-to-image-pixel-art

---

The official github repository for the university-project:
> “Developing a Diffusion Pipeline for Optimization of Video Game Asset Generation”
> by Valentino Pecchinenda (github@vvvlntno) and  Danny Seidel (github@DannySeidel)

This repository includes the report and the code.

---

To run the code there are two methods.
1. Run it locally (requires powerful NVIDIA GPU & atleast 16GB of RAM)
2. Run it on google colab

---

To run the code locally follow this process:
1. Clone the repository
2. On your machine, go into the `code` folder
3. If not installed, install [anaconda](https://www.anaconda.com) and create the environment using `conda env create -f text-to-image-pixel-art.yml`
4. Install the right version of [pytorch](https://pytorch.org) for your system
5. Use your favorite editor to open the `.ipynb` file
6. Go to the cell below `Create prompts`, here you can change the prompts how you like, it is best to leave the “displayed from the front showing the whole body in the middle of the screen with a clear grey background” in the prompt for the performance
7. Now you can run everything, except the `pip install` part, these are for the colab notebook
8. You can see your result in the last cell on the bottom
![Result Image](https://github.com/vvvlntno/text-to-image-pixel-art/blob/main/result.png?raw=true)

---

To run the code in google colab follow this process, google account required:
1. Go to your [google drive](https://drive.google.com/drive/u/1/my-drive) and create a new folder to paste the notebooks from the repository
2. Open the colab notebook using right click on the file and open with `Google Colaboratory`
3. Go to the cell below `Create prompts`, here you can change the prompts how you like, it is best to leave the “displayed from the front showing the whole body in the middle of the screen with a clear grey background” in the prompt for the performance
4. Now you can run everything and see your output in the cell below
![Result Image](https://github.com/vvvlntno/text-to-image-pixel-art/blob/main/result.png?raw=true)

--- 

As you can see the output is pixel perfect, meaning that it fits the pixel art style, this would have not been possible without the two models used, [Stable Diffusion XL](https://stability.ai/stable-image) and the LoRA [Pixel Art XL](https://civitai.com/models/120096/pixel-art-xl) from [Nerijs](https://civitai.com/user/NeriJS).

