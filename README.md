# ChatScrub Search Generator

A simple, browser-based tool for generating search commands for Discord chat scrubbing. This tool allows you to easily create search strings with multiple keywords and channel IDs without having to manually format them.

## Features

- **Simple Keyword Input**: Easily add multiple search terms
- **Channel ID Management**: Add, edit, and save Discord channel IDs
- **Custom Display Names**: Create friendly names for cryptic channel IDs
- **One-Click Generation**: Generate properly formatted search strings with a single click
- **Copy to Clipboard**: Copy the generated command with one click
- **Export/Import**: Save your channel configurations for future use
- **Runs Locally**: Works completely in your browser with no server requirements

## Installation

No installation required! Simply download the HTML file and open it in any modern web browser.

```bash
# Clone the repository (if applicable)
git clone https://github.com/yourusername/chatscrub-generator.git

# Or just download the HTML file directly
```

## How to Use

### Basic Usage

1. **Add Keywords**: Enter the keywords you want to search for in the top input field
2. **Add Channel IDs**: 
   - Enter a Discord channel ID in the "Add Discord Channel IDs" field
   - Optionally give it a display name to help you remember what the channel is
   - Click "Add Channel" (or press Enter)
3. **Generate Command**: Click "Generate Search String" to create your search command
4. **Copy Command**: Click "Copy to Clipboard" to copy the generated string
5. **Paste in Discord**: Paste the command in Discord to execute your search

### Channel Management

- **Add Channels**: Enter channel IDs and optionally provide friendly display names
- **Edit Names**: Click the pencil icon (✎) next to a channel to edit its display name
- **Remove Channels**: Click the × button to remove a channel
- **Select Channels**: Use checkboxes to include/exclude specific channels from searches
- **Clear All**: Use the "Clear All" button to remove all saved channels

### Saving Your Configuration

Your channel configuration only persists for the current browser session. To save it for future use:

1. Click "Export Channels" to generate a configuration string
2. Copy the text from the text area and save it somewhere safe (e.g., in a text file)
3. To restore your configuration later, paste the saved text and click "Import Channels"

## Command Format

The generated search command follows this format:

```
!find keyword1 keyword2 ... <#channel-id1> <#channel-id2>
```

This format works with standard Discord chat scrubbing tools.

## Technical Details

- Built with pure HTML, CSS, and JavaScript
- No external dependencies or libraries
- Works in all modern browsers
- All data is stored in memory only - no cookies or localStorage used
- Channel data is stored as JSON for easy export/import

## License

This tool is provided as-is, free to use and modify for any purpose.

## Contributing

Feel free to fork this repository and make improvements. Pull requests are welcome!

---

Created for use with Discord chat scrubbing tools. Not affiliated with Discord, Inc.
