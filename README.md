# Shtick City for Mac

Downloads for the Mac app of [Shtick City](https://shtick-city.sager.click), the open-world browser game
set in UT Austin's West Campus on Friday, September 8, 2006. This repository holds only the app
downloads; the game itself is free to play in a browser at **shtick-city.sager.click**.

**Download:** [Shtick-City-mac.dmg](https://github.com/jaycosaygr/shtick-city-mac/releases/latest/download/Shtick-City-mac.dmg)
(about 270 MB; one app for Apple silicon and Intel Macs, macOS 12 Monterey or later).
Full install steps: **[shtick-city.sager.click/mac](https://shtick-city.sager.click/mac)**.

## Before you install

The app is not signed with an Apple Developer ID and is not notarized by Apple. macOS will warn
that it "can't be opened because Apple cannot check it for malicious software" (or that it is
"damaged"). That is expected for an independent build; the steps on the install page explain how
to open it anyway. Only download it from this page or from shtick-city.sager.click.

## Install

1. Download `Shtick-City-mac.dmg`, open it, and drag **Shtick City** into **Applications**.
2. Open Shtick City from Applications. macOS blocks the first launch:
   - **macOS 15 Sequoia and later:** click **Done** on the warning, open **System Settings → Privacy & Security**,
     scroll to "Shtick City was blocked…", click **Open Anyway**, then confirm with your password.
   - **macOS 12 to 14:** Control-click (or right-click) the app in Applications, choose **Open**, then **Open** again.
3. If macOS says the app is **damaged**, clear the download flag once in Terminal and open it again:

   ```
   xattr -dr com.apple.quarantine "/Applications/Shtick City.app"
   ```

After the first launch it opens normally.
