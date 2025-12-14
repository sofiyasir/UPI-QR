# UPI-QR
A simple web-based tool to generate UPI payment QR codes instantly using a UPI ID, helping users receive payments accurately and quickly.
##  Problem Statement
Whenever I needed to receive payments, I had to share my UPI ID with the payer manually.  
This was frustrating because:
- UPI IDs are hard to remember and type correctly
- Users often made mistakes while entering the UPI ID
- Sometimes, people paid using my phone number instead of my UPI ID
- Payments occasionally went to a different bank account linked to my number
Because of these issues, receiving payments was unreliable and inconvenient.
##  Solution
To solve this problem, I built **QuickUPI QR**.
This tool:
- Generates a UPI payment QR code instantly
- Ensures payments go to the correct UPI ID
- Eliminates typing errors
- Allows users to save the QR code in their gallery and reuse it anytime
## Features
- Instant UPI QR code generation
- Supports any UPI ID (GPay, PhonePe, Paytm, Amazon Pay, etc.)
- Displays UPI ID and account holder name with the QR
- Safety confirmation before generating QR
- No data storage — works fully on the client side
- Clean and responsive UI

## Tech Stack
- HTML
- CSS
- JavaScript
- QRCode.js library

## How to Use
1. Enter your UPI ID
2. (Optional) Enter account holder name
3. Confirm the safety checkbox
4. Generate the QR code
5. Save the QR and receive payments easily

## 🔐 Privacy & Security

- No payment processing happens on this website
- No user data is stored or tracked
- QR codes are generated locally in the browser

