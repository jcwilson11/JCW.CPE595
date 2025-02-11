# CPE595
Spring 2025: CPE 595 - Applied Machine Learning

## COURSE DESCRIPTION
An introductory course for machine learning theory, algorithms, and applications. The content
aims to provide students with the knowledge to understand key elements of how to design
algorithms/systems that automatically learn, improve, and accumulate knowledge with
experience. Topics covered in this course include decision tree learning, neural networks,
Bayesian learning, reinforcement learning, ensembling multiple learning algorithms, and various
application problems. Students will be provided opportunities to simulate their algorithms in a
programming language and apply them to solve real-world problems.

## Course Workflow
This course requires I use Anaconda becuase of its built in virtual environment (venv) feature. I will include a step by step procedure for working within the venv, as it will be helpful for me, and perhaps benefit others who visit this repo. The steps are relevant only if you have already installed Anaconda, and have setup a venv already. Replace `CPE595` with the name of your venv

1. Open Anaconda Prompt or Terminal
2. Navigate to your GitHub repo:
   `cd -> repo`
3. Activate your environment:
   `conda activate CPE595`
4. Launch Jupyter Notebook:
   `jupyter notebook`
5. Work on assignments and take notes.
6. Save changes and push to GitHub

If running `jupyter notebook` does not work, try installing the following inside of the venv
```
conda activate CPE595
conda install -c conda-forge jupyter
conda update jupyter_server notebook
conda install -c conda-forge traitlets
jupyter notebook
```
