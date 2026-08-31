# Developer website root: app-ads.txt

This folder contains the seller list to publish at:
https://magicode118.github.io/app-ads.txt

It is separate from the existing app website at:
https://magicode118.github.io/tripleplaydrawpoker-pages/

## Publish on GitHub Pages

1. Open (or create) the GitHub repository named `magicode118.github.io` under the `magicode118` account.
2. Put `app-ads.txt` in the root of that repository's Pages publishing source. The exact filename is `app-ads.txt`, not `app_ads_txt.txt` or `app-ads.txt.txt`.
3. If a root `app-ads.txt` already exists by the time you upload, merge these entries with it; preserve valid entries for other apps and advertising providers.
4. For branch-based publishing, select Settings > Pages > Deploy from a branch, then the branch and folder containing the file (normally `main` and `/(root)`). Preserve an existing Pages workflow if the repository already has one.
5. After deployment completes, open https://magicode118.github.io/app-ads.txt and check that the seller list appears as plain text, not a 404 or HTML page.
6. Keep the app's Google Play developer website set to https://magicode118.github.io/tripleplaydrawpoker-pages/. Its host matches the root seller-list URL.
7. Allow Appodeal and advertising partners time to crawl the published file; successful website deployment does not mean they have verified it yet.

Uploading only to the `tripleplaydrawpoker-pages` project repository would put the file in the wrong subfolder. No game-code changes, APK, AAB, or Play release are needed for this website update.

## Source and checks

Prepared from the supplied Appodeal export `app_ads_txt.txt` (header: Updated 31.03.2026).

- The AdMob `Publisher_ID` and Meta `Business_ID` template records are commented out, because these networks are not connected for this app. Do not publish placeholders as active seller records. If you connect your own account later, obtain its verified entry from that network.
- One empty optional fourth field was removed: `adsphere360.com, 1042770, RESELLER,`.
- All other seller records and IDs are preserved from the export, including Google's reseller entries. These entries do not add the AdMob SDK to the game.
- There are 2,504 active seller records. Basic formatting was checked; seller ownership and each network's authorization were not independently verified.
- The original downloaded file was not changed.

Refresh this list when Appodeal supplies updates. If multiple apps use this developer website host, the root file should contain the combined authorized seller entries they need.

## Official instructions

- Appodeal: https://faq.appodeal.com/en/articles/3183799-app-ads-txt-support
- Your Appodeal export: https://app.appodeal.com/user_profile/ads_txt
- GitHub Pages: https://docs.github.com/en/pages/quickstart
