# notes
My notes

## To run in a web interface
Viewer:
https://nbviewer.jupyter.org/github/yoomlam/notes/blob/master/python_notebook/doc_type_stats.ipynb

Binder:
https://mybinder.org/v2/gh/yoomlam/notes/master?filepath=python_notebook/doc_type_stats.ipynb

## To run locally
```
docker run -i -t -p 8888:8888 continuumio/anaconda3 /bin/bash -c "/opt/conda/bin/conda install jupyter -y --quiet && mkdir /opt/notebooks && /opt/conda/bin/jupyter notebook --notebook-dir=/opt/notebooks --ip='*' --port=8888 --no-browser"
```

