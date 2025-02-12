# Vodafone Mobile Number Validator
This project is designed to validate Vodafone mobile numbers using regular expressions in UiPath. The workflow prompts the user to input a mobile number, checks if it matches the Vodafone number format, and logs whether the number is valid or invalid.

# Workflow Overview
User Input: The workflow prompts the user to enter a Vodafone mobile number.

Regex Pattern: A regular expression pattern is defined to match valid Vodafone mobile numbers.

Validation: The workflow checks if the entered number matches the defined regex pattern. as Vodafone Keys (100,101,102,103,104,105,106,109)
				Number must Contain one of country key in beginning (+0020,0020,20,0,+20)
				routing numbers are 7 after the Country and operator key.

Logging: If the number is valid, it logs "valid Vodafone mobile number". If invalid, it logs "Invalid Vodafone mobile number".
