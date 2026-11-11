[README.md](https://github.com/user-attachments/files/34667075/README.md)
# Mboa Express Savings

A small browser-based prototype for managing rotating savings pools. The interface supports English and French, with payment options that change according to the selected country.

## Run locally

No installation or server is required. Open `mboa-pool-manager.html` in a modern web browser.

The prototype saves its demo state in the browser's local storage. Each browser has its own data; member lists, payments, and settings are not synchronized between users.

## Features

- Select a pool by contribution amount and frequency: weekly, every two weeks, or monthly.
- Create pools with one or two payout recipients and a member limit of up to 100.
- View cycle contributions, payout totals, a closing countdown, and member payment status.
- Submit a deposit for manual admin confirmation and choose an XAF admin fee.
- Apply a 3% late fee after a cycle closes.
- Switch the interface between English and French.
- Select Cameroon, the United States, France, or Canada to see the corresponding payment-method list.
- View member names and profile pictures; phone numbers and ID numbers are shown in the prototype's admin view.

## Payment options shown

- **Cameroon:** Orange Money, MTN MoMo, and cash deposit.
- **United States:** Zelle, Cash App, Apple Pay, PayPal, Venmo, and debit/credit card.
- **France:** Apple Pay, PayPal, bank transfer, and debit/credit card.
- **Canada:** Interac e-Transfer, Apple Pay, PayPal, and debit/credit card.

These are display options only. The prototype does not connect to payment providers or move money. Pool amounts and fees are currently displayed in XAF for every country.

## Publish with GitHub Pages

1. Create a GitHub repository and upload both `mboa-pool-manager.html` and this `README.md`.
2. In the repository, open **Settings → Pages**.
3. Choose the `main` branch and `/ (root)` as the publishing source, then save.
4. Open the published Pages URL and append `/mboa-pool-manager.html` to view the app.

## Prototype limitations and safety

This is a front-end demo, not a production financial application. The member/admin switch is not authentication, browser storage is not secure or shared, and user-entered contact and ID details are not protected by a server. The payment options, account settings, deposits, and admin confirmations are not connected to real financial services.

Do not use real identity, contact, banking, or payment information in this prototype. Before handling real users or money, it needs a secure backend, real authentication and authorization, protected storage, verified payment-provider integrations, and appropriate legal and regulatory review.
