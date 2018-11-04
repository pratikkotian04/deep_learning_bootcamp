# deep_learning_bootcamp


Docker Commands

docker ps -a


docker rm -f ga-dl

sudo nvidia-docker run -itd -p 8888 --volume=/home/$USER/notebooks:/home/jovyan/notebooks --name=ga-dl --ipc=host saiprasadb/ga-dl-workshop:latest jupyter notebook --no-browser --ip=0.0.0.0 --allow-root --NotebookApp.token= --notebook-dir='/home/jovyan/'
