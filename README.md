<h1 align="center">
  <br>
  <a href="https://github.com/mkdirlove/Gork"><img src="https://github.com/mkdirlove/gork/blob/main/logo.png" alt="CXSecurity"></a>
  <br>
  Yet another tool for dorking.
  <br>
</h1>

#### Installation

Copy-paste this into your terminal:

```sh
git clone https://github.com/mkdirlove/Gork.git
```
```
cd Gork
```
```
python3 -m pip install requests beautifulsoup4 selenium webdriver-manager
```
```
python3 gork.py
``` 

#### HOW SEARCH WORKS:
```
- "Selenium (Chrome)" mode opens a real Chrome browser, logs in as you,
  and scrapes results — Google cannot tell it apart from a human.
- "Requests" mode is fast but Google will CAPTCHA-block it quickly.
- "Open in Browser" always works — it just opens your default browser.
```
