# AH Health Alert Google Sheets Script

## Overview

This Google Apps Script is built to automate the validation of health-related data entries in a Google Sheet used by the AH program. It supports rule-checking for various health metrics such as sleep, MVPA, steps, wearable sync, junk food, fruit and vegetable intake, BP, and more.

The script ensures:
- Accurate logging of participant data
- Triggering alerts/nudges based on predefined thresholds
- Language-specific message generation (English & Chinese)
- Automatic handling of weekday-based schedules

---

## Features

- ✅ Validates complex health behavior rules (e.g., MVPA > 3x/week)
- 🔄 Handles multiple languages
- 🗓️ Supports weekday-specific scheduling
- 📊 Evaluates 7-day averages, frequency checks, and value thresholds
- ⚠️ Adds alerts/nudges directly into the Sheet

---

## Setup

1. Open your Google Sheet.
2. Click **Extensions > Apps Script**.
3. Copy-paste the script into the editor.
4. Save and authorize required permissions.
5. Use `runScript()` or bind to triggers as needed.

---

## Example Rules

- **Not wearing the watch alert**: <60% wear time avg. over 3 days.
- **MVPA nudge**: If MVPA is logged more than 2x/week.
- **Suboptimal Wellness Score**: <60 avg over 7 days.
- **Fruit and Vegetables Alert**: <3 serves on 5 of last 7 days.

---

## Maintenance

- Regularly check the script for any updated rule logic.
- Ensure Sheet column names and formats match expectations.
- Modify thresholds directly in the script as needed.

---

## Author

This script was developed as part of the AH health monitoring initiative. For questions or updates, please contact the development team.
