# chrome-cors-disable
Open Chrome without cross-origin (CORS) security on Mac

Quit chrome and run the following command from your terminal

```bash
open -n -a /Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome --args --user-data-dir="/tmp/chrome_dev_test" --disable-web-security
```
