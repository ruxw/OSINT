🕵️ OSINT Tool by Twistens (@Twistens)

This is an Open Source Intelligence (OSINT) tool designed to gather information about an email, phone number, or username. It checks whether the provided input is linked to popular websites and services, retrieves metadata such as phone number carrier and location, and performs username lookups across multiple platforms.

🚀 Features

✅ Email Lookups:

Checks if an email is registered on major websites like Twitter, Instagram, TikTok, Snapchat, Vimeo, SoundCloud, ACAPS, DarkWebID, NewsAPI, and more.

📱 Phone Number Info:

Retrieves country, ZIP code, carrier, and possible name data.

🔍 Username Recon:

Scans all URLs provided in Links.txt to find if the username exists on those platforms.

📦 Requirements

Python 3.x
Install the dependencies with:

pip install requests phonenumbers

🛠️ How to Use

Clone the Repository:

git clone https://github.com/Twistens/osint-tool.git
cd osint-tool


Prepare Links File (for username scanning):

Create a file named Links.txt

Add URLs using {} as a placeholder for the username.

https://github.com/{}
https://twitter.com/{}
https://instagram.com/{}
https://t.me/{}


Run the Script:

python osint.py


Select a Mode:

1 → Search for Email

2 → Search for Phone Number

3 → Search by Username

99 → Exit

🧪 Example Inputs
[+] Enter Email : someone@example.com
[+] Enter Phone Number: 974 55512345
[?] Enter Username : twistens

📁 File Structure
osint-tool/
│
├── osint.py         # Main script
├── Links.txt        # List of platform URLs for username checks
├── README.md        # This file

📜 License

This project is licensed under the GNU General Public License v3.0. See LICENSE file for details.

⚠️ Legal Disclaimer

This tool is intended only for educational and lawful use. Using this software to collect information about individuals without consent may violate privacy laws in your jurisdiction. Use responsibly and at your own risk.

Would you like me to save this as a downloadable README.md file for you?