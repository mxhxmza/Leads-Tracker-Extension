# Leads Tracker Extension

A lightweight Chrome extension (Manifest V3) for saving and tracking leads — URLs, contacts, or notes — as you browse. Save your current tab with one click, or manually add a custom entry, then revisit or clear your saved leads anytime from the popup.

## Features

- **Save Tab** — instantly saves the URL of your current browser tab as a lead
- **Save Input** — manually add a custom link, note, or lead description via the text field
- **View Saved Leads** — all saved entries are listed in the popup for quick reference
- **Delete All** — clear every saved lead in one click
- Built on **Manifest V3** using the `tabs` permission

## Tech Stack

- HTML / CSS / vanilla JavaScript
- Chrome Extensions API (`chrome.tabs`, `chrome.storage`)

## Project Structure

```
Leads-Tracker-Extension/
├── manifest.json    # Extension configuration (Manifest V3)
├── index7.html       # Popup UI
├── index7.css        # Popup styling
├── index7.js         # Core logic (save, list, delete leads)
└── image.png          # Extension icon
```

## Installation (Load Unpacked)

1. Clone or download this repository:
   ```bash
   git clone https://github.com/mxhxmza/Leads-Tracker-Extension.git
   ```
2. Open Chrome and navigate to `chrome://extensions`
3. Enable **Developer mode** (toggle in the top-right corner)
4. Click **Load unpacked**
5. Select the folder containing this repository
6. The Leads Tracker icon will appear in your Chrome toolbar

## Usage

1. Click the extension icon to open the popup
2. Click **SAVE TAB** to save the URL of the page you're currently on
3. Or type a link/note into the input field and click **SAVE INPUT** to save it manually
4. Your saved leads appear in the list below
5. Click **DELETE ALL** to clear all saved leads

## Roadmap / Ideas

- [ ] Add per-item delete instead of delete-all-only
- [ ] Add timestamps and lead notes/tags
- [ ] Export saved leads to CSV
- [ ] Search/filter saved leads
