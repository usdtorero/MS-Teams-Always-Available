# Microsoft Teams: Always Available

This Chrome extension keeps your Teams status as `Available` (or Away/Busy) by calling the same
presence endpoint your browser session already uses. It runs locally in your browser and does not
require any subscription or external service.

**Note**: I do not personally support the use of this functionality in a workplace.

## Compatibility

- Works with the classic Teams web experience at `https://teams.microsoft.com`.
- Teams 2.0 is not supported at this time.

## Installation (load unpacked)

1. Clone or download this repository.
2. Open Chrome and navigate to `chrome://extensions`.
3. Enable **Developer mode**.
4. Click **Load unpacked** and select this repository folder.
5. Open `https://teams.microsoft.com` and sign in.
6. Use the extension popup to enable the status you want to keep.

## Usage notes

- The extension uses your existing Teams login session, so keep a Teams tab open.
- You can limit execution to a time window from the popup settings.
