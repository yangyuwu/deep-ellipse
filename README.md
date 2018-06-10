# Deep Ellipse

### Setup

1. Clone this repo in some directory (e.g. 'deep-ellipse')
2. Extract the images in the same dir (so you have 'deep-ellipse/images/train' etc.)
3. From `deep-ellipse`, run `pip install -r requirements.txt`
4. Run `jupyter nbextension enable  --py widgetsnbextension`
5. From `deep-ellipse`, run `jupyter notebook --NotebookApp.token=""`
6. Navigate your browser to `http://localhost:8888/notebooks/deep-ellipse.ipynb#`

> NOTE: if you're on linux and pip is run unpriviliged you may end up with the correct `jupyter` executable in `~/.local/bin` (which may not be on the `PATH`). If you get an error like `Error executing Jupyter command '*'` this is most likely the cause. If so, in step 3+4 simply use `~/.local/bin/jupyter` instead of `jupyter`