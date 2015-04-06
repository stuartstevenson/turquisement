# turquisement

a bluegreen deployment tool

\#shipit

given an artifact
when the artifact is a package
then unpack the package

given an artifact and target environment
then I should be able to ssh to the target env

given an artifact and target env
when I ssh to the target env
then I should deploy the artifact to the fallow dir

given the fallow dir is not empty on the target env
then I should empty the dir and deploy the artifact into it

given the deployment dir
when the dir contains an init.sh script
then execute the init.sh


