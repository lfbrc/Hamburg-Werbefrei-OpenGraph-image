# Hamburg Werbefrei - OpenGraph image template to automatically share images in networks and messengers

This is a simple template for embedding images when sharing links.

## About This Repository

This repository is the place where a test page for the implementation of images via OpenGraph tags is provided as an example.

### How to use

Copy the OpenGraph tags into the head section of your HTML page.

#### Brief explanation:

* og:image = absolute path to the image to be displayed when sharing

* og:image:width/height = self-explanatory

* g:url = absolute path to the page to be shared

* og:title = the subject that is to be displayed

* og:description = introductory text

* All other tags are recommended, but optional

### Notes

Set all urls to an absolute address on the corresponding web server - the messenger and sharing sites access this information externally.

### Example
https://lfbrc.github.io/Hamburg-Werbefrei-OpenGraph-image/

### Testing

This test page:
https://www.opengraph.xyz/url/https%3A%2F%2Flfbrc.github.io%2FHamburg-Werbefrei-OpenGraph-image

Live system:
https://www.opengraph.xyz/url/https%3A%2F%2Fwww.hamburg-werbefrei.de

### First results (testet on iOS 18.3) with the following apps

Messages:

![Messages on iOS](/assets/testing/messages-ios-18.3.jpg)

Telegram:

![Telegram on iOS](/assets/testing/telegram-ios-18.3.jpg)

Signal:

![Signal on iOS](/assets/testing/signal-ios-18.3.jpg)

Mastodon:

![Mastodon on iOS](/assets/testing/mastodon-ios-18.3.jpg)

Perhaps the shareimage should be adjusted in the proportions, so that it works for all services.

For more information on the widely used Open Graph protocol look here:
https://ogp.me

If you have any questions, you can join the “HWF Technik neu” group on Signal. Thank you very much!

Images: © 2025 Hamburg Werbefrei

---
Version history:

20250211 - Initial commit  
20250212 - Add Mastodon screenshot to REDAME
