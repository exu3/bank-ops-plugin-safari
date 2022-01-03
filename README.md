# Hack Club Bank Operations Plugin (for Safari)

This a port of the original [hackclub/bank-ops-plugin](https://github.com/hackclub/bank-ops-plugin) Chrome extension which can be used in Safari on macOS or iOS. See the [hackclub/bank-ops-plugin](https://github.com/hackclub/bank-ops-plugin#readme) repository for a more comprehensive description of what this extension does.

## Run extension in Safari (macOS)

1. Clone this repository / open it in Xcode.
2. Configure Safari in macOS to run unsigned extensions.
    - Choose Safari > Preferences > Advanced.
    - Check the "Show Develop menu in menu bar" option.
    - In the menu bar, choose Develop > Allow Unsigned Extensions.
3. In Xcode, select the macOS app in the Scheme menu next to the Run button at the top.
4. Click the Run button to build the app. You should see the HCB icon in the toolbar in Safari.
5. Enter the magic key.
6. Wahoo! It should work now.
  
## Set up in Safari (iOS)

Not really possible (yet).
