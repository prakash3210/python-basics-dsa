I am Arjun Sharma and this is my testing repository authentication using SSH.

…or create a new repository on the command line

echo "# test" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/2309arjunsharma/test.git

git push -u origin main

…or push an existing repository from the command line

git remote add origin https://github.com/2309arjunsharma/test.git

git branch -M main

git push -u origin main


To create and activate this environment, 
use                                                                                                                                                      

$ conda create -p venv python==3.12

$ conda activate C:\workspaces\python-workspaces\test\venv                                                                                                                         

To deactivate an active environment, use

$ conda deactivate

Command: conda install -n venv ipykernel --update-deps --force-reinstall

pip install -U ipykernel


If you want to not use Ananconda/Conda then use python in build virtual environment

python3 -m venv venv

source ./venv/bin/activate


