# QuarterDeck — Privacy

Version 0.32.0 · Effective: 2026-11-10 · Contact: quarterdeckui@gmail.com

**QuarterDeck sends no data to us.** There is no account, registration, analytics (telemetry) or advertising. Your tasks, conversations, settings and measurements stay on your computer, in QuarterDeck's data folder in your user profile.

**What is read on your computer.** While "Show AI work on this computer" is on, QuarterDeck reads the start and end of the conversation files that Claude Code, Codex, Gemini CLI and Antigravity keep in your user folder, process information of running programs, and quota information. These are shown on screen and do not leave the computer. You can turn this off at any time.

**Connections the program makes on its own** (each can be turned off under Preferences → Automatic network use):
- At most one update check a day: the public `latest.json` file on GitHub is downloaded. Nothing about your computer is added to the request.
- Quota reading and model lists: the quota/model commands of the AI programs you installed, and the model list of your API connections (sent to that company with your key). No question is ever sent to a model in the background.
- Price list: when a model without a saved price is chosen, a public price list is downloaded.
- Phone view: only when you turn it on, an encrypted port opens on your computer so your phone on the same local network can connect (on Windows, Windows Firewall asks about it). It is not opened to the internet and closes when you turn it off.

**Work you start.** When you start a task or an Agora session, your request and the project files the agent needs go to the AI company you chose (Anthropic, OpenAI, Google and others) through that company's program or your API key. Their processing is governed by that company's privacy terms.

**Support and gift codes.** When supporting, you send us your machine code (QD-…) yourself. It is a digest derived from your hardware; it contains neither your name nor your files. To send the gift code, your name, e-mail, machine code and the date are recorded and used only for that purpose (to send the code again if you lose it); they are shared with no one. You can ask for their deletion at quarterdeckui@gmail.com. Payments go through Buy Me a Coffee or GitHub Sponsors; your card details never reach us.

**Crash reports** stay on your computer; they reach us only if you send them.
