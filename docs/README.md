📢 Use this project, [contribute](https://github.com/vtex-apps/cookie-script) to it or open issues to help evolve it using [Store Discussion](https://github.com/vtex-apps/store-discussion).

# Cookie Script

<!-- DOCS-IGNORE:start -->
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-0-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
<!-- DOCS-IGNORE:end -->

Cookie Script first party integration app. The [solution](https://cookie-script.com/) makes your website cookies comply with GDPR and CCPA.

![image](https://user-images.githubusercontent.com/284515/86488877-d35b0f80-bd38-11ea-95f9-7610985e19d5.png)

## Vtex Configuration

It is possible to install the Cookie Script in your store either by using App Store or the VTEX IO Toolbelt.

### Using VTEX App Store

1. Access the **Apps** section in your account's admin page and look for the Cookie Script box;
2. Then, click on the **Install** button;
3. You'll see a warning message about needing to enter the necessary configurations. Scroll down and type in your **Cookie Script ID**.
4. Click on **Save**.

### Using VTEX IO Toolbelt

1. In your terminal, [install](https://vtex.io/docs/recipes/development/installing-an-app/) the `vtex.cookie-script@0.x` app. You can confirm that the app has now been installed by running `vtex ls` again. 
2. Access the **Apps** section in your account's admin page and look for the Cookie Script box. Once you find it, click on it.
3. Fill in the **Cookie Script ID** field.
4. Click on **Save**.

## Cookie Script Configuration

On the *Cookie scanner* tab, run a scan. After the scan is complete, go to *Cookies* tab and make sure the following cookies are categorized as "Stricly Necessary": ASPXAUTH, checkout.vtex.com, CookieConsent, device, vtex_segment, vtex_session, VtexFingerPrint, VtexRCMacIdv7, VtexRCRequestCounter, VtexRCSessionIdv7 and VtexWorkspace.

<!-- DOCS-IGNORE:start -->
## Contributors ✨

Thanks goes to these wonderful people:

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind are welcome!
<!-- DOCS-IGNORE:end -->
