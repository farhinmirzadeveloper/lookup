lookup

Python utility to perform phone number lookup and carrier validation using the Twilio Lookup API.

This tool reads phone numbers from a CSV file and generates a result CSV containing carrier and line type details.

Features
Bulk phone number lookup
Carrier detection
Line type identification
CSV input and output support
Uses Twilio Lookup API
Simple command-line execution
Requirements
Python 3.x
Twilio Account SID
Twilio Auth Token

Install required package:

pip install twilio
Environment Variables

Linux/macOS:

export TWILIO_ACCOUNT_SID=your_account_sid
export TWILIO_AUTH_TOKEN=your_auth_token

Windows CMD:

set TWILIO_ACCOUNT_SID=your_account_sid
set TWILIO_AUTH_TOKEN=your_auth_token
Input CSV Format

Example: phone_numbers.csv

phone_number
+14155552671
+919876543210
Usage
python lookup.py phone_numbers.csv
Output

The script generates an output file:

phone_numbers.csv_results.csv
Purpose

This project is intended for learning, testing, communication workflow validation, and development purposes using Twilio cloud communication APIs.

Disclaimer

This project is provided for educational and development purposes only. Users are responsible for complying with all applicable laws, regulations, and Twilio Terms of Service.