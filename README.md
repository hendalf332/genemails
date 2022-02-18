# genemails
pip install getemails

Python module for generating random emails and names and surnames Initially import:

from genemails import GET_EMAIL

To generate one random email:

email=GET_EMAIL.generate_email()

To generate many emails use:

manyemails=GET_EMAIL.generate_emails(15) #It will return string separated by comma

To get random 1st or surname name:

fisrtname=GET_EMAIL.get_firstname()

surname=GET_EMAIL.get_sndname()

To Generate random address and telephone number:

data['address'],data['tel']=gml.generate_address()

for example: 'address': 'UnitedKingdom city.Bangor str.Bell Inn Yard h.63 ft.182' To generate specific email based on real name pass parameters:

email=gml.generate_email(firstname=data['firstname'],secondname=data['sndname'])
