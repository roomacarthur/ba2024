# Boutique Ado 2024

Updated version of Boutique ado built with python 3.12.2 in mind. 

Python version 3.12.2

## Key Differences

Below are the key differences from the Original source code, this repo only contains the files with changes to streamline the differences. 

### [settings.py](https://github.com/roomacarthur/ba2024/blob/main/boutique_ado/settings.py)

Updated the way that envrionment variables are used form the walkthrough, this now includes the use of env.py.

### [checkout/webook_handler.py](https://github.com/roomacarthur/ba2024/blob/main/checkout/webhook_handler.py)

Updated the intent charges handling to match that of the [Novembver 16th 2022 ](https://stripe.com/docs/changelog#november-16,-2022) update.

### [requirements.txt](https://github.com/roomacarthur/ba2024/blob/main/requirements.txt)

Some packages have been updated as seen in the requirements.txt file, specifically Django, Django-Allauth, Stripe and some other minor changes
