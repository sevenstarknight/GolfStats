# GolfStats
Golf Statistics Analysis

## Prerequisites

- Build a virtual environment ([How-To](https://python.plainenglish.io/python-virtual-environments-explained-78d5a040f963))
  -  in a terminal window: python -m venv venv
  -  activate the virtual env: 
    - Linux: `source ./venv/bin/activate`  
    - Windows: `.\venv\Scripts\activate`
    - (if issue occurs see: [fix](https://www.sharepointdiary.com/2014/03/fix-for-powershell-script-cannot-be-loaded-because-running-scripts-is-disabled-on-this-system.html))
  -  In Linux, you'll see your terminal window you'll get a new start to the line (venv). In Windows, you can run a Python command (e.g. `python -c "print (\"Hello World\")"` and you should see (venv) display when the execution finishes.

- Imports: from the terminal window (with the venv prefix) install your updates  
  - Check to see if you have pip installed, if not: Install/Update [pip](https://pip.pypa.io/en/stable/installation/)
  - Run: pip install -r requirements.txt (potentially you might need to do this within python; i.e. python/py/python3 -m in front of pip)
  - Alternatively Ensure that you have pipreqs installed locally (pip install pipreqs)
  - to generate freeze of requirements "pipreqs --force"

- To test your distributon run all tests: python -m unittest discover -s unittests