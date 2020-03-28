first write this command it will ask to overwrite please say yes:

    Jupyter lab --generate-config

then open this notebook_config.py file from this location

    C:\Users\username\.jupyter\jupyter_notebook_config.py

paste this line at the end of the file and save it.

    c.NotebookApp.browser = "C:/Program Files (x86)/Google/Chrome/Application/chrome.exe --app=%s"
