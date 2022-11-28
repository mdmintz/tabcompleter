# tabcompleter

**[tabcompleter](https://github.com/mdmintz/tabcompleter)** is a friendly fork of the (unmaintained) [fancycompleter](https://github.com/pdbpp/fancycompleter) package. **tabcompleter** lets you use the **Tab** key to expand and autocomplete options in the Python console.

<img width="550" alt="tabcompleter" src="https://user-images.githubusercontent.com/6788579/204385233-838cbfbf-6ec7-4b45-812c-d0c2556a82e8.png">

### Installation:

```bash
pip install tabcompleter
```

### Usage:

```python
import tabcompleter
tabcompleter.interact(persist_history=True)

# Now use the Tab key in the Python console
```

An example of using the **Tab** key to see all possibilities:

<img width="550" alt="tabcompleter" src="https://user-images.githubusercontent.com/6788579/204386211-5fc44f73-e29f-4e87-b0ca-bb8ea69217af.png">

### More examples:

**tabcompleter** is used by packages such as ``pdbp`` and ``seleniumbase``:

* https://github.com/mdmintz/pdbp
* https://pypi.org/project/pdbp/
* https://github.com/seleniumbase/SeleniumBase
* https://pypi.org/project/seleniumbase/
