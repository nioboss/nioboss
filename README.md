<h2 align="center">About Me </h2>

```python
from typing import Tuple, List, Dict

class HaAnhTuan:
    pass

class Attributes(HaAnhTuan):
    @property
    def contact(self) -> Tuple[str, str, str]:
        facebook  = "nio.devpy"
	telegram  = "@nio2k9"
        email     = "thsoftware.vn@gmail.com"
	    
	    return facebook, instagram, proton

    @property
    def life(self) -> Tuple[List[str], int]:
        langs = ['Vietnamese']
        age   = 14

        return langs, age
	
    @property
    def coding(self) -> Tuple[Dict[str, List[str]], List[str], List[str]]:
        langs = {
            'expert'      : ['python'],
            'intermediate': ['go', 'js'],
            'learning'    : ['c', 'c++', 'c#', 'asm', 'java']
        }
        specialities  = ['web/app reverse engineering', 'fullstack']
	environnement = ['vscode']

	return langs, specialities, environnement
```
<h2 align="center">Skills </h2>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,golang,vscode,androidstudio,c,cs,cpp,js,css,html" />
  </a>
</p>
