# DBS Ind Butterfly — White & Gold Compact UI

This version updates the practice interface to better match the supplied DBS reference:

- White app background instead of black
- Yellow/gold header area
- Smaller text, cards and icons
- Compact four-button action row
- Compact Insights card
- Home balance remains hidden as `********`
- Tap **Account** to view the fixed displayed balance
- Butterfly app icon retained
- Installed app name: **DBS Ind**

This is a standalone practice interface. It is not connected to DBS Bank, UPI, or any real banking service.


## Balance display update

- Home shows the fixed balance immediately after login.
- The Account card remains clickable.
- Account details show:
  - Available balance
  - Linked deposited balance
  - Net withdrawal amount balance

The linked deposited balance is set to ₹0.00 in this demo, so the net withdrawal amount balance matches the available balance.

## App icon/name refresh v9

This build uses a new PWA app ID, versioned manifest, and newly named butterfly icon files so browsers do not reuse the older "DBS Demo" install metadata.

Installed app name: **DBS Ind**


## Header fix v10

Home now shows only **Welcome digibank by DBS**.
