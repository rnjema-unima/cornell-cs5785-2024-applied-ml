# COM424 - Machine Learning
> [Adapted from Kuleshov Applied ML course at Cornell University](https://kuleshov-group.github.io/aml-book)

## Instructions for Use
  - There are a number of ways of viewing these presentations,
     - You may view as Jupyter notebooks, in which case you may spawn a JupyterLab/Hub local instance to serve these notebooks or may make use of VSCode Jupyter environment
       - To spawn a JupyterLab instance, run the following command in the directory containing the notebooks
          ```bash
            jupyterlab .
         ```    
         - In this case, make sure [Jupyter RISE](https://rise.readthedocs.io/en/latest/) is installed.
     - Alternatively, you may convert the notebooks into  RevealJs-backed slide templates. Use the following to convert all slides to RevealJs slides
        ```bash
        jupyter nbconvert *.ipynb --to slides
       ```
        - In this case, you may now serve the produced HTML templates using a built-in Python HTTP server module as follows - 
            ```bash
                python -m http.server <PORT_NUMBER>
            ```
            - where you can specify port number to spawn the server on (when ignored, the default port is **8000**).