# Use fastai for ml in google colab

- The `fastai` ml related packages are available in fastai version `0.7`. The default 
installed `fastai` has version `>1.0`
- Install version `0.7` in google colab using `!pip install fastai==0.7.0`. Symbol `!` helps
to run any `bash cmd` in the jupyter cell.
- Uploading files in google colab is little tricky and some browser may give error. Better use 
google chrome. File loading code snippet

```py
from google.colab import files
files.upload()
```

- [Notebooks](https://github.com/fastai/fastai/tree/master/courses/ml1)
- [Lecture Videos](http://course18.fast.ai/ml)

## [Optional] Use nbviewer
- If the notebooks are not rendered in github use [nbviewer](https://nbviewer.jupyter.org/)
- Put the github `.ipynb` notbook link in the `nbviewer`
