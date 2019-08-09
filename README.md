# MBDU Project template

This is an example of a suggestion for how to layout MBDU projects on felix.  
Data should be at MBDU/bids/projectname and the data directory here should symlink to that.  
The output of processing pipelines goes in data/derivatives.  
The env directory should be createed by conda with a `conda create -p ./env ....` command used to create the conda environment for this project.  
Processing scripts, code, notebooks, etc. go in the notebook directory, which should probably be a github repo in its own right.  
The swarm directory is for swarm commands and log files organized by pipeline and run.  
