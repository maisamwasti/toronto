
## Experimenting Virtual Enviroments

### Helper commands

To open a file from terminal to a text editor  
`open -a TextEdit readme.txt` 

### Setup in Python (Conda)

Virtual Environments are there just there to isolate the libraries in python. We have these in Conda and PIP

https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-python.html

https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/

`conda create -n yourenvname python=x.x anaconda`   
Remove `anaconda` above if I want to create an empty VENV

`conda create -n ds27 python=2.7 anaconda`

https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#create-env-file-manually

`conda env export > environment.yaml`


`conda env create -f environment.yml` #To Create from YAML file

Here I have learnt how to create a virtual enviroment, the links has details of it. And then after installing packages, I can export a YAML file, that can be shared and other's can use it to recreate the same enviroment.

## Experimenting Containers/Dockers



## Experimenting Flask (api)
