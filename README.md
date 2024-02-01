<h2 align="center">About Me </h2>

```python
from typing import Dict, List, Tuple

class DeveloperProfile:
    pass

class AboutMe(DeveloperProfile):
    @property
    def contact(self) -> Dict[str, str]:
        return {
            'GitHub': 'idkconsole',
            'Telegram': 'idkconsole',
            'Email': 'idkconsole@proton.me'
        }

    @property
    def bio(self) -> Dict[str, Union[str, int]]:
        return {
            'Name': 'console',
            'Age': 16,
            'Interests': 'Innovating the web one line of code at a time.'
        }

    @property
    def skills(self) -> Dict[str, List[str]]:
        return {
            'Languages': ['English'],
            'Programming': {
                'Basic': ['Python'],
                'Currently Learning': ['HTML', 'CSS', 'JavaScript']
            }
        }

    @property
    def goals(self) -> Tuple[str, List[str]]:
        aspiration = 'Aspiring full-stack developer'
        goals = [
            'Build a personal project portfolio',
            'Contribute to open source',
            'Learn backend development'
        ]
        return aspiration, goals
```
<h2 align="center">Skills </h2>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,vscode,androidstudio,js,css,html" />
  </a>
</p>
