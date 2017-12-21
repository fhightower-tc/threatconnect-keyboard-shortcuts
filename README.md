# ThreatConnect Keyboard Shortcuts

Keyboard shortcuts for [ThreatConnect](https://app.threatconnect.com) power-users.

## Disclaimer

These shortcuts were not created by ThreatConnect and I am not responsible for any damage incurred using these shortcuts. If you have feedback or suggestions, please raise an [issue](link).

## Installation

These keyboard shortcuts are designed to working with a Google Chrome extension. As such, you will need [Google Chrome](https://www.google.com/chrome/index.html) or will need to see if there is a comparable extension in your favorite browser.

0. Install the [Shortcut Keys](https://chrome.google.com/webstore/detail/shortkeys-custom-keyboard/logpjaacgmcbpdkdchjiaagddngobkck) extension for Chrome.
1. Edit the shortcut keys options by navigating to [chrome://extensions/](chrome://extensions/), finding the entry for the "Shortkeys (Custom Keyboard Shortcuts)" extension, and clicking "Options".
2. Copy the text from the tc_shortcuts.json in this repository.
3. Navigate to the "Import" tab of the dialog box and paste the content you copied from tc_shortcuts.json.
4. Click the "Import" button and you should be good to go! If you are logged into ThreatConnect, you will have to refresh the page before the shortcuts are available. 

## Usage

Most of the shortcuts are made up of three or four letters. For example, one of the keyboard shortcuts is: `b i a`. To use this keyboard shortcut, you would type the letter "b" then "i", then "a" in relatively quick succession.

The first letter specifies the **action**. The possible actions are:

- `b`: Browse
- `c`: Create
- `n`: Navigate

If the first letter is `b` (browse) or `c` (create), the second letter specifies the **type** of the item we would like to take action on. The possible types are:

- `g`: Groups
- `i`: Indicators
- `t g`: Tags
- `t r`: Tracks
- `v a`: Victim Assets
- `v m`: Victims

Alternatively, if the first letter of the keyboard shortcut is `n` (navigate), the second (and sometimes third) letter(s) specifies the **location** to which you would like to navigate. The possible locations are:

- `a`: Analyze
- `b`: Browse
- `d`: Dashboard
- `i s`: Structured Import
- `i u`: Unstructured Import
- `m`: My Profile
- `o c`: Org. Config
- `o s`: Org. Settings
- `p`: Playbooks
- `s`: Spaces

If the first letter is `b` (browse) or `c` (create), the third (and sometimes fourth) letter(s) are used to specify the **subtype** of the indicator or group we would like to action on. The possible subtypes for *indicators* are:

- `a`: Address
- `e`: Email Address
- `f`: File
- `h`: Host
- `u`: URL

The possible subtypes for *groups* are:

- `a`: Adversary
- `c`: Campaign
- `d`: Document
- `e`: Email
- `i`: Incident
- `s`: Signature
- `t a`: Task
- `t h`: Threat

There are a few, miscellaneous shortcuts that do not fit the format described above:

- `o w`: Specify an owner
- `shift+b g`: Browse to all groups
- `shift+b i`: Browse to all indicators
- `shift+n`: Create a new playbook (this only works when you are on the [playbooks page](https://app.threatconnect.com/auth/playbooks/index.xhtml))

## Examples

- `b i f`: This will *browse* for *file indicators*
- `c g t h`: This will *create* a *threat*
- `n p`: This will navigate to the [playbooks page](https://app.threatconnect.com/auth/playbooks/index.xhtml)
