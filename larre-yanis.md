import requests
adresse = "88 avenue verdier"
url_ban_example = f"https://api-adresse.data.gouv.fr/search/?q={adresse.replace(" ", "+")}&postcode=92120"
requests.get(url_ban_example)