## Installation

To be able to run the code and experiments in this repository, follow these steps:

1. Install Anaconda: 

   - Visit the [Anaconda website](https://www.anaconda.com/products/individual) and download the installer for your operating system.
   - Follow the installation instructions provided for your specific OS.

2. Clone this repository:
```
git clone https://github.com/mees707/AML-feather-in-focus
```
3. Navigate to the project directory:
```
cd AML-feather-in-focus
```
4. Create a new Anaconda environment:

   Open a terminal (or Anaconda Prompt on Windows) and run the following command, which installs the requirements according to the environment file we provide:
   ```
   conda env create -f environment.yml
   ```
   
5. Activate the environment:
  ```
  conda activate feather-in-focus
  ```
6. Alternative using pip
   If you prefer using pip, you can also install the environment using the requirements file we supplied
   ```
   pip install -r requirements.txt
   ```
7. Running Jupyter Notebook:
   If you haven't worked with Jupyter Notebook yet, you should set up jupyter so that you can select the right kernel and work with the packages we just installed.
   ```
   ipython kernel install --name "feather-in-focus" --user
   ```