![python](https://img.shields.io/badge/python-2.7-brightgreen.svg) ![license](https://img.shields.io/badge/license-GPL-brightgreen.svg)
# Infoga - Email Information Gathering
Infoga is a tool for gathering e-mail accounts information from different public sources (search engines, pgp key servers). Is a really simple tool, but very effective for the early stages of a penetration test or just to know the visibility of your company in the Internet.

## Screenshot
![screen1](https://raw.githubusercontent.com/m4ll0k/Infoga/master/screen1.png)

## Installation
```
git clone https://github.com/m4ll0k/Infoga.git infoga
cd infoga
pip install -r req
python infoga.py
```
## Example
`python infoga.py --target fbi.gov --source all`
`python infoga.py -t fbi.gov -s all`

![screen2](https://raw.githubusercontent.com/m4ll0k/Infoga/master/screen2.png)
