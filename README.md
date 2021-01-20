# git-directory-download

## Install
`python3 -m pip install -r requirements.txt && chmod +x gitd && ./gitd`

## Usage
```
usage: gitd [-h] [-u URL] [-r] [-p] [--proxy PROXY]

optional arguments:
  -h, --help         show this help message and exit
  -u URL, --url URL  github url, split by ",", example: "https://x, http://y"
  -r, --raw          download from raw url
  -p, --parse        download by parsing html
  --proxy PROXY      proxy config, example "socks5://127.0.0.1:7891"

Example:
  1. download by raw url: gitd -u "https://github.com/twfb/git-directory-download"
  2. download by raw url: gitd -r -u "https://github.com/twfb/git-directory-download"
  3. dowmload by parsing: gitd -p -u "https://github.com/twfb/git-directory-download"
  4. download by raw url with proxy: gitd -r -u "https://github.com/twfb/git-directory-download" --proxy "socks5://127.0.0.1:7891"
```
