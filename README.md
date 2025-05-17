# ARİVA LeakOsint Tool

🌟 **ARİVA LeakOsint Tool** is a Python-based OSINT (Open-Source Intelligence) tool designed for educational purposes. It allows users to query various data types such as usernames, phone numbers, emails, and more through the LeakOsint API. 

⚠️ **Disclaimer**: This tool is intended for **educational and ethical use only**. Any illegal usage is strictly prohibited, and the developers are not responsible for misuse. Use at your own risk.

📢 **Join our community**: [Telegram @ArivaTools](https://t.me/ArivaTools)  
🎨 **Designed by**: @AtahanArslan  
🚀 **Version**: 1.0.0

## Features
- Query multiple data types:
  - Social media usernames (Instagram, Twitter, Telegram, Facebook, VK, etc.)
  - Phone numbers, emails, names, INN, passports, license plates, SNILS, IDs, and more
- Colorful and user-friendly CLI interface using `pystyle`
- Automatic dependency installation
- Version checking for updates
- Cross-platform support (Windows, Linux, Termux)

## Prerequisites
- Python 3.6 or higher
- Internet connection
- A valid LeakOsint API token (obtain from [LeakOsint]}

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ArivaTools/arivaosintv4.git
   cd arivaosintv4
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   Alternatively, the tool will automatically attempt to install required modules (`pystyle`, `requests`) on first run.

3. Run the tool:
   ```bash
   python arivaosintv4.py
   ```

## Usage
1. Launch the tool:
   ```bash
   python ariva_leakosint.py
   ```
2. Follow the on-screen menu:
   - Select option `[1]` to start a query.
   - Enter the data to query (use `;` to separate multiple queries, e.g., `username;email;phone`).
   - Provide your LeakOsint API token.
   - View the results displayed in the console.
   - Select `[0]` to exit.

3. Example query:
   ```
   Sorguyu girin (birden fazla için ; kullanın): example_user;+1234567890;test@example.com
   LeakOsint token'ını girin: your_api_token_here
   ```

## Screenshots
![ARİVA LeakOsint Banner](screenshots/banner.png)
*Banner displayed on tool startup*

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

## Legal Notice
This tool is provided for **educational purposes only**. The developers are not responsible for any misuse or illegal activities conducted with this tool. Always ensure compliance with local laws and regulations when performing OSINT activities.

## Contact
- 📢 Telegram: [@ArivaTools](https://t.me/ArivaTools)
- 🎨 Developer: [@AtahanArslan](https://t.me/AtahanArslan)
- 📧 Issues: Create a [GitHub Issue](https://github.com/ArivaTools/ARIVA-LeakOsint/issues)

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

🌟 **ARİVA LeakOsint Tool** - Empowering ethical OSINT research!  
🚀 Follow us on [Telegram](https://t.me/ArivaTools) for updates!