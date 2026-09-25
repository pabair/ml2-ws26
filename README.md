# Maschinelles Lernen 2
Code-Repository für den Kurs "Maschinelles Lernen 2" an der Hochschule Karlsruhe.

# Setup

The recommended way to setup your development environment is to use Anaconda:
1. Download and install Miniconda for your OS from here: [https://docs.conda.io/en/latest/miniconda.html](https://docs.conda.io/en/latest/miniconda.html)

2. Start the `Anaconda Prompt` on Windows. On Mac or Linux, just open a new terminal window.

3. Create a new environment for this course:

`conda create --name ml2 python=3.8`

4. Activate this environment:

`conda activate ml2`

5. Install the following packages: numpy, pandas, matplotlib, scikit-learn.

`conda install numpy pandas matplotlib scikit-learn jupyter`

6. Install Pytorch and follow the instructions [here](https://pytorch.org/get-started/locally/). You do not need the GPU support, CPU is enough.

7. Test your installation by opening a new jupyter notebook. A new browser window should open.

`jupyter notebook`


