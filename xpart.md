# **x-path Cheat sheet**
<bar>


## **X-Path Notebook Setup Guide**


```
1. Project Directory Creat. 
2. X-path Notebook Creat.
3. h.html File creat.
4. Copy Python x-path boiler code From Notebook.
5. Copy HTML code from Chrome Browser
6. run and check [response] 
```



## **X-Path python Boiler code**
<bar>

```python
from parsel import Selector

with open("h.html", "r") as f:
    html = f.read()
    response = Selector(text=html)


response
```


## **X-Path Content Selection 3 Rules**
```
1. //tag/text()  # This on for text selection.
2. //tag@href    # This on for url selection
3. //tag@src     # This on for image selection
```

## **X-Path Element selection Rules**

```
1. Support tag
2. End tag

rules 1
Support file start to be //tag

rules 2
attribute start tag selection 
//tag[@attribute_name=value] 


```