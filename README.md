# Introduction Image-Processing with Python
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/johnny-vo/image-proc-binder/main?labpath=notebooks%2Findex.ipynb)

This jupyter-notebook will be based on the lecture image processing M70. Python will be used to teach basic techniques and algorithms for image processing. Students will get an insight into the world of python. Upon this they will use it to process images.
In the following course the students should be able to calculate and evaluate certain parameters of images. They should learn to implement different methods for image processing in the spatial and frequency space. 
This includes e.g. methods for denoising, edge detection and compression. 

## Setting up Environment on Local Machine 
### Installation of Conda on macOS
1. Open up Terminal and paste in Shell Prompt `xcode-select --install`
2. After Installation of the Command Line Tool for Xcode paste in the same Shell Prompt `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
3. Follow the Instructions of the brew Installer
4. Re-open the Terminal and paste `brew install --cask anaconda`
5. Paste in Shell Prompt `export PATH="/usr/local/anaconda3/bin:$PATH"`
6. To make the export permanent paste in Shell Prompt `source ~/.zshrc`


### Installation of Conda on Windows
1. Visit [Anaconda Website](https://www.anaconda.com/products/distribution#windows) and download the Python 3.9 64-Bit Graphical Installer
2. Follow the Instructions of the Installer
3. After Installation you should have an additional Command Prompt installed (anaconda3) 
For further questions follow this [site](https://medium.com/@GalarnykMichael/install-python-anaconda-on-windows-2020-f8e188f9a63d)

### Setup Conda Environment 
1. Clone this repository either via `git clone` or downloading this Repo as zip-file
2. Open up Terminal (macOS) or Anaconda Prompt (Windows) and change Directory to the cloned Repo
3. Paste `conda env create -f environment.yml` into the Shell Prompt to create the Environment
4. Install ipykernel into Conda with `conda install -c anaconda ipykernel`
5. After Installation of ipykernel type `python -m ipykernel install --user --name=image-proc` into the Shell Prompt 







