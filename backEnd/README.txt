Conda
Activate the environment after you create the environment: `conda activate lms`
Create an environment from the .yaml `conda env create --file environment.yaml`
Install new dependencies: `conda env update --file local.yml`
Add a new dependency: `conda install packageName`
You've gotta update the environment.yaml by hand though.

Note for windows users: Conda will not work with powershell :(