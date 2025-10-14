# Instant-UPI-Splitter-MVP
Defensive publication for Instant UPI Splitter MVP flow
Instant UPI Splitter – MVP Flow (Defensive Publication)

Date: 14 October 2025
Author: Shlok R. Lotake

Description

Instant UPI Splitter is a mobile app prototype that allows friends to split bills, collect payments via UPI apps, handle declined payments, allow retries, redistribute unpaid amounts, and share receipts. Payments are completed through standard UPI apps (Google Pay, PhonePe, Paytm, BHIM, etc.), with no new UPI authorization flow or merchant automation.

Core Steps / User Flow

Scan Merchant QR

App owner opens the app and scans the merchant’s QR code (restaurant, cafe, ride, etc.).

Choose Split Method

Options:

Split equally among participants

Custom split per participant

Add Participants

Add each friend’s contact number, phone number, or UPI ID.

App owner can choose to include themselves or remain excluded from the split.

Send UPI Payment Requests

Participants receive payment requests on their UPI apps.

Payments are completed via standard UPI apps.

Declined or ignored requests do not go through.

Handle Declined Payments

App owner is notified if any participant declines.

Options:

Retry sending the request.

Proceed with only confirmed payments.

Redistribute remaining unpaid amount among participants who confirmed (equally or custom).

Volunteer payment by any participant for an unpaid share.

Complete Payment to Merchant

Merchant receives total payment only after confirmed payments or after app owner decides how to handle declined amounts.

App updates status for each participant (paid, pending, declined, redistributed, or volunteer-covered).

Track Payments and Share Receipts

Tracks total collected, pending, and declined payments.

Provides option to share the receipt with all participants for transparency and record-keeping.

Example Scenario

Three friends share a ₹1,500 dinner bill.

Friend A (app owner) scans merchant QR, adds Friend B and Friend C, includes themselves.

Friend B pays; Friend C declines.

Friend A retries the request; Friend C still declines.

Friend A chooses to redistribute the unpaid portion among participants who confirmed or pays only the confirmed amount.

After finalizing payments, Friend A shares the receipt with all participants.

Goal

Provide a flexible, transparent, and user-controlled way to split bills among friends, handle declined payments intelligently, allow retries, redistribute unpaid amounts, and share receipts, ensuring the merchant receives payment only after confirmations or app owner approval, using standard UPI apps.

✅ Benefits as Defensive Publication

Publicly documents full MVP user flow.

Includes declined payments, retries, redistribution, volunteer payments, and receipt sharing.

Confirms all payments use standard UPI apps, reducing legal risk.

Serves as timestamped prior art to protect against future patent claims.


