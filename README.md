# Browser Restrictions (Registery files)

Simple `.reg` files to enforce browser restrictions using Windows policies.

## Files

* **disable-incognito.reg**
  Disables Incognito / Private mode in Chromium-based browsers.

* **google-safe-search.reg**
  Forces Google SafeSearch (strict). Does not affect YouTube.

* **disable-guest-mode.reg**
  Removes Guest browsing option.

## Supported Browsers

Chrome, Chromium, Brave, Edge, Opera, Vivaldi, Yandex, Epic, Slimjet, Comodo Dragon, SRWare Iron, Avast Secure Browser, AVG Secure Browser

## Exceptions

* Firefox (uses different policy system)
* Tor Browser
* Non-Chromium browsers
* Portable / modified builds (may ignore policies)

## Usage

1. Double-click `.reg` file
2. Accept prompt
3. Restart browser

(Admin required)

## Notes

* Works system-wide
* Harder to bypass than DNS
* No undo included (revert manually)

---
