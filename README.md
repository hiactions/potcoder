![PotCoder Screenshot](https://github.com/hiactions/potcoder/blob/main/src/potcoder/assets/potcoder-screenshot.png)

<a href='https://discord.gg/mVR8EpdM' target="_blank"><img alt='Discord' src='https://img.shields.io/badge/Join_Our COmmunity-100000?style=for-the-badge&logo=Discord&logoColor=FFFFFF&labelColor=5865f2&color=5865f2'/></a>
<a href='https://pypi.org/project/potcoder/' target="_blank"><img alt='pypi' src='https://img.shields.io/badge/PyPI_Download-100000?style=for-the-badge&logo=pypi&logoColor=FFFFFF&labelColor=515153&color=232A79'/></a>

## Requirements
The table below lists all Python versions that PotCoder supported:
| Python Version | Supported |
| :---: | :---: |
| 3.5 | ☓ |
| 3.6 | ☓ |
| 3.7 | ☓ |
| 3.8 | ✔ |
| 3.9 | ✔ |
| 3.10 | ✔ |
| 3.11 | ✔ |
| >= 3.12 | ✔ |


## How to Install & Use

### Install
Install via `pip` (Recommended):
```
pip install potcoder
```


Install via `whl` file:
- Go to Release > Select latest version of PotCoder > Press the file with the name `potcoder-[potcoder-version]-py3-none-any.whl`
- After download, run this command:
```
pip install potcoder-[potcoder-version]-py3-none-any.whl
```

### Use
- To be able to add the PotCoder module to your Python file, add the command `import potcoder` at the beginning of the Python file.
- You can also add individual functions to the file via the `from potcoder import [function]` command (See the functions available in the latest version of PotCoder under [#Functions](#functions))

## PotCoder CLI
- Usage: `potcoder.cli()`

## Functions
| Functions | Syntax (Usage) | Uses |
| :-- | :-- | :-- |
| conv_str_bin | `potcoder.conv_str_bin([Machine Question])` | Converts strings to binary code |
| cli | `potcoder.cli()` | See [#CLI](#potcoder-cli) for more information |
| pygpt | `potcoder.pygpt([API Key], [Model ID], [Machine Question])` | ChatGPT built with Python |
| pyenv_detect | `potcoder.pyenv_detect()` | Python Runtime Environment Checker |
| ytdl | `potcoder.ytdl([Machine Question], [Successful download message], [Error download message])` | Download high quality Youtube videos |





