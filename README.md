# glastoselenium

Adapted from thomasms to add a crude UI, not great at the moment but I think it's sort of working. you still need to locate the selenium drivers and install the glasto package. 


Set the path to the driver via:
```bash
export CHROMEDRIVER=/path/to/chromedriver
```

Try:
```bash
python3 glasto_main.py
```

Requires a webdriver - only tested with chromedriver (http://chromedriver.chromium.org/)



Can use the package as:
```python
import glasto as gl
...
```

Alternatively, the first version exists on PyPI and can be installed directly using pip:

```bash
pip3 install glasto
```



Some test sites are being added to the submodule test/sites - https://github.com/thomasms/testsites.

These mimic a real life web site that needs a lot of refreshing.


One React SPA exists so far. 

Just run it locally via npm
```bash
cd test/sites
npm start
```

Then test the client script:
```bash
python test/testsite1.py
```
