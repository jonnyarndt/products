# Support for Bellhop Cue

Thanks for using Bellhop Cue! Below you'll find answers to common questions and ways to get help.

---

## Frequently Asked Questions

**Where does Bellhop Cue appear on my Mac?**
Bellhop Cue is a **Dock-based** app. When you launch it, the **Settings** window opens automatically. After you close the window, Bellhop Cue continues running quietly in the background. To reopen Settings, click the Bellhop Cue icon in the Dock.

**How do I change the notification interval?**
Open **Settings** and go to the **General** tab. In the **Time** section, use the **Clock Boundary** picker to choose **Hourly**, **30-Min**, or **15-Min**.

- **Hourly** — alerts fire at the top of every hour (:00)
- **30-Min** — alerts fire at :00 and :30
- **15-Min** — alerts fire at :00, :15, :30, and :45

These are clock-boundary alerts, not countdown timers based on when the App was launched.

**How do I change the notification sound?**
Open **Settings** and go to the **Sound** tab. You can pick from:

- **Grandfather Clock** — recorded Westminster chimes with quarter-hour phrases and hourly bong strikes that match the current hour
- **Built-in** — 14 standard macOS system sounds (Basso, Blow, Bottle, Frog, Funk, Glass, Hero, Morse, Ping, Pop, Purr, Sosumi, Submarine, Tink)
- **Custom** — import your own **MP3** or **M4A** file using the **Browse** button

Clicking any sound in the list immediately plays a live preview. Use the **Volume** slider to adjust playback level.

**How do I change the visual notification?**
Open **Settings** and go to the **Visual** tab. Use the **Visual Mode** picker to choose:

- **Flash** — a full-screen white/black flash. Use **Flash Count** to set 1–5 cycles per alert.
- **Image (Bundled)** — displays one of 7 built-in graphics (abstract, clock, or nature themes).
- **Image (Custom)** — import your own **PNG** or **JPEG** file.

For image modes, you can also adjust **Display Duration** (1–60 seconds), **Opacity** (0–100%), and toggle **Fade In / Out**.

**Will Bellhop Cue interrupt me when I'm using Focus Mode or Do Not Disturb?**
By default, Bellhop Cue fires regardless of your Focus Mode state. If you'd like it to stay silent while Focus Mode is active, open **Settings → General**, find the **Behavior** section, and enable the **Respect Focus / DND** toggle.

**Which monitors does the visual notification appear on?**
Open **Settings → General** and find the **Display** section. Set **Monitors** to either **Primary Monitor** or **All Monitors**.

**Can I turn audible or visual notifications off independently?**
Yes. Open **Settings → General** and use the **Audible Notifications** and **Visual Notifications** toggles in the **Notification Channels** section.

**How do I test Bellhop Cue or export diagnostics?**
Open the App's help screen and choose **Test Bellhop Cue Now** to trigger a test alert, or **Export Diagnostics** to save a local diagnostics file in the App's container.

**How do I quit Bellhop Cue?**
Right-click the Bellhop Cue icon in the Dock and choose **Quit**, or use **Command-Q** while the Settings window is focused.

**How do I uninstall Bellhop Cue?**
Drag Bellhop Cue from your **Applications** folder to the Trash. To also remove saved preferences, run the following in Terminal:
```
defaults delete com.jonnyarndt.bellhop
```

**Does Bellhop Cue collect any of my data?**
No. Bellhop Cue does not collect, store, or transmit any personal data. Imported custom sounds and images, if you choose them, are stored locally on your Mac. See the full [Privacy Policy](https://jonnyarndt.github.io/products/bellhop/privacy-policy/) for details.

---

## Still Need Help?

If you're experiencing an issue not covered above or have a feature request, you're welcome to open a ticket on GitHub:

[Open an Issue on GitHub](https://github.com/jonnyarndt/products/issues/new)

Please include the product name (Bellhop Cue), your macOS version, and a description of the problem or request.