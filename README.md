# Avarwand PWE (Persian Wikipedia Editor)

A professional, Python-based tool designed for automating and improving content editing on **Persian Wikipedia Articles**.  
With an intuitive graphical interface, it provides rule-based text corrections, category management, and page content cleanup for maintaining linguistic and formatting consistency across Persian Wikipedia articles.

---

## Main Features

- **Smart Text Correction**: Automatically standardizes Persian grammar, spelling, and half-spaces using regex-based rules.
- **Category Management**: Detects, adds, and validates Wikipedia categories related to geography, literature, and Iranian studies.
- **Pywikibot Integration**: Securely connects to Persian Wikipedia using Pywikibot for page read/write operations.
- **Custom Rule Editing**: Built-in GUI for creating, editing, cloning, and testing new language normalization rules.
- **Unicode Support**: Fully supports UTF-8 Persian text, diacritics, and zero-width non-joiners.
- **Safe Config Handling**: Automatically saves and manages configuration files, including user credentials and JSON rule sets.
- **Multi-threaded Operations**: Performs background updates without freezing the interface.
- **GUI Built with Tkinter**: User-friendly design optimized for Persian right-to-left layout and Tahoma font readability.

---

## System Requirements

- **Operating System**: Windows (recommended) or Linux (with GUI support)
- **Python Version**: 3.9 or later  
- **Dependencies**:
  - `pywikibot`
  - `tkinter` (standard in Python)
  - `json`, `re`, `threading`, and other standard libraries  
  *(all installed automatically or included with Python)*

---

## Usage

1. **Launch the Application**  
   Run `Persian Wikipedia Editor.py` with Python 3.x.

2. **Configure Pywikibot**  
   On first startup, the app will prompt you to select or create your `user-config.py` file for authentication.

3. **Manage Rules**  
   - Open the "Rule Manager" from the GUI.  
   - Add, edit, or clone normalization rules as needed.  
   - Save changes to automatically update your `rls.json` file.

4. **Process Wikipedia Pages**  
   - Connect to Persian Wikipedia (`fa.wikipedia.org`).  
   - Apply your correction rules to selected articles.  
   - Review, verify, and save the results.

---

## Logging and Configuration

- **Configuration File**: `config.json` (auto-managed by the app)
- **Rule File**: `rls.json` (user-defined rule set)
- **Temporary Files**: Automatically handled and cleaned up in the system temp directory

All actions, warnings, and status updates are displayed within the GUI and optionally logged for debugging.

---

## Common Issues

- **Login Errors**: Ensure your `user-config.py` points to the correct Pywikibot directory.
- **Permission Denied**: Run as administrator if file access errors occur.
- **Encoding Issues**: Always save rule and config files in UTF-8 format.

---

## Technical Details

- **Language Support**: Persian (Farsi)
- **Automation Layer**: Pywikibot API
- **GUI Framework**: Tkinter
- **Text Processing**: Regex-based normalization rules
- **License Type**: Freeware (Avarwand License)

---

## Contributing

This software is released as **freeware** by **Avarwand**.  
Suggestions, bug reports, and improvement ideas are welcome.  
If you have new normalization rules or categories to contribute, please contact the author directly.

---

## License

This software is released as freeware under the following terms:

**END USER LICENSE AGREEMENT (EULA)**  

This software, **Avarwand PWE**, is provided by **Avarwand** and **P. Avarwand**, free of charge for personal and commercial use.  

By installing or using this software, you agree to:
- Use the software in compliance with the EULA  
- Not reverse engineer, decompile, or modify the software  
- Not redistribute or claim ownership of the software  
- Accept the software "as is" without warranties  

*For full EULA terms, see the LICENSE file in the distribution.*

---

**Developed by Payam Avarwand**  
**Initial Release: July 2025**  
**Last Updated: October 2025**

## Contact

**Payam Avarwand**  
Email: payam_avar@yahoo.com  

© 2025 Avarwand. All rights reserved.
