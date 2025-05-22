# Test Case: Reset password flow

# Title: Password reset flow validation

# Preconditions: User must be on the login page

# Steps to reproduce: 
        1. Do not provide email or password
        2. Clock on "Forgot your password?" option
        3. User gets redirected on Password Reset Page
        4. System is asking user to provide their email address
        5. User proceeds and a new field appears where the generated passkey is entered (in case the email address is an existing one)
        6. System to send an email containing a passkey of six randomized numbers
        7. User to copy the numbers into the passkey field

# Expected result: Password Reset system to work as intended
# Actual result: 

# Status: Not executed