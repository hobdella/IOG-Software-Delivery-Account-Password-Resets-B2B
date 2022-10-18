# IOG-Software-Delivery-Account-Password-Resets

B2B / RISK Domain Password ResetsPassword reset policies and standards for B2B and RISK Domain accounts.

Please note that resetting AD passwords should only be done for individuals who have Windows devices. Using AD or recommending the Azure Password Reset for should not be done on for any Mac users because of the additional troubleshooting that is required.

B2B Domain:
Users must first pass security question to authenticate their identity. 

1. If the user is present with you their staff ID pass can be requested.

If remote: 
2. B2B Only: Authenticate using Post Code Checker in SharePoint
or
3. Challenge for Employee ID> Authenticate from AD

If the caller is unable to confirm their identity using any of the above methods their manager (as recorded in AD) must approve the unlock and confirm their identity.

NOTE: A password reset for 3rd party accounts (POI/CWR) must always be approved by the individuals manager.

Password Standards:
* Password complexity:
* Minimum 8 characters
* Minimum 1 upper case
* Minimum 1 numeric
* Cannot use a password that has been used within the last 5 password changes



Things to remember;
1. You must always use a strong password generator: https://lastpass.com/generatepassword.php (8 characters, at least 1 upper and 1 numeric). DO NOT use the same generic password for every reset. 
2. Non-company email is is not a trusted method of communications and passwords cannot be passed to/from personal email accounts. A request for a password reset from a personal email address must be approved by the account holders manager.
3. We must never write both the email address / username and password on the same piece of paper.
4. New passwords should not be entered in to TOPdesk tickets.
