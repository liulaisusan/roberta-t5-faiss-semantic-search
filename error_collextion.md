# Error Collection 
## Installation
- No module called:... error  
    After `pip install -r requirements.txt` is still not enough. Some of the packages are still missing. Just install them via `pip` and try run `python app.py` again.
- TypeError: Required argument `height` was not specified.  
    This happened after all the packages are installed. It is beacues the version of `dash`, `dash-bootstrap-components` and `dash-mantine-components` version are different from the origianl one. Just reinstall with the proper version listed in [requirements.txt](requirements.txt)
    
