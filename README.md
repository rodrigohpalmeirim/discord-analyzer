# Discord Analyzer

A command-line tool for scanning and analyzing Discord servers, displaying several statistics in the form of tables and charts.

> [!NOTE]
> This project is no longer maintained (built in 2021). It logs in with a user account token, which goes against Discord's Terms of Service and is no longer supported by recent versions of `discord.py`, so it is kept here for reference only.

## Features

### Server scanning

A group of channels from a server can be selected to be scanned.

Scans include all the messages in the selected channels including other relevant information (reactions, mentions, etc...).

The scans can later be updated by scanning only the new messages.

### Analysis

After the scan is completed, an analysis is performed, compiling all relevant information for each user, channel, emoji and the server.

Analysis do not contain the messages' text, so they can be safely shared.

### Importing and Exporting

Scans and analysis can be exported and imported to/from JSON files.

### Data visualization

Tables and charts can be generated, displaying metrics and ranks.

Metrics analyzed include:
- Messages
- Characters typed
- Characters per message
- Emoji used
- Reactions
- Mentions
- Replies
- Links
- Attachments
- Messages per hour of the day
- Messages per day of the week

Some filters can be applied to the data displayed (e.g. column selection, user roles)

## Installation and Usage

To install Discord Analyzer run:
```
pip install discord-analyzer
```

To execute run:
```
discord-analyzer
```