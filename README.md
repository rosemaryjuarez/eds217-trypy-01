# eds217-trypy-01
day 2!!!! thursday and friday are left

also theres nothing interesting to note, but im writing this at 2:37 pm. lets hope i leave at 4 cuz i wanna go see my rats!!

also extra stuff that was asked:

"""
Create a new variable containing 
the link to the .csv file on 
the EDS_221 github repository.
"""
url = 'https://raw.githubusercontent.com/'\
'allisonhorst/EDS_221_programming-essentials/'\
'main/activities/stl_blood_lead.csv'

""" 
pandas can read a csv file into a 
dataframe directly from a url:
"""
stl_lead = pd.read_csv(url)
