# Resume_Builder
A python-based resume builder project that takes user input and generates a well-structured resume.Built using core python concepts
name=input("Enter the name:")
knownlang=input("Enter the known languages:")
skills = {}
skills["Programming LANGUAGES:"] = input("Enter programming skills:")
skills["Tools"] = input("Enter tools known: ")
contact = {}
contact["contact Number:"]=input("Enter the mobile number:")
contact["Email ID:"]=input("Enter the Email ID:")
string=input("Enter whether your beginner or not:")
if(string=="beginner"):
    profile="Motivated B.Tech standard seeking an internship opportunities to apply programming knowledge in C,Java,Python,ehance problem-solving skills,and gain real-world industries experience"
else:
    profile=input("Enter your profile:")
Education={}
Education["college"]=input("Enter the college name:")
perdetails={}
perdetails["DATE OF BIRTH"]=input("Enter the date of birth:")
perdetails["LOCATION"]=input("Enter the current location:")
perdetails["NATIONALITY"]=input("Enter the nationality:")
Achievements={}
Achievements["Certificates"]=input("Enter the certificates gained:")
Achievements["Medals"]=input("Enter the medals obtained:")
print("Select the design as per your reqiurement:")
print("designs:\na)1-simple\nb)2-moderate\nc)3-high level\nd)4-Extra high level")
design=input("Enter the number:");
if(design=="1"):
     print("---------------------------------------------------------------")
     print(name.center(20))
     print("---------------------------------------------------------------")
elif(design=="2"):
     print("***************************************************************")
     print(name.center(20))
     print("***************************************************************")
elif(design=="3"):
     print("===============================================================")
     print(name.center(20))
     print("===============================================================")
elif(design=="4"):
    print("++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++")
    print(name.center(20))
    print("++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++")
print()
print("* PROFILE:",profile)
print()
print("*EDUCATION")
print("-"*10)
for key,value in Education.items():
    print(f"{key}: {value}")
print()
print("*TECHNICAL SKILLS")
print("-"*10)
for key,value in skills.items():
    print(f"{key}: {value}")
print()
print("KNOWN LANGUAGES:",knownlang)
print()
print("*ACHIVEMENTS")
print("-"*10)
for key,value in Achievements.items():
    print(f"{key}: {value}")
print()
print("*CONTACT DETAILS")
print("-"*10)
for key,value in contact.items():
    print(f"{key}:{value}")
print()
print("*PERSONAL DETAILS")
print("-"*12)
for key,value in perdetails.items():
    print(f"{key}: {value}")
print("The above mentioned details are true")





Enter the name:RANGU KEERTHANA
Enter the known languages:Telugu,Hindi,English
Enter programming skills:C,Java,Python
Enter tools known: VS code,Jupyter
Enter the mobile number:xxxxxxxxxxx
Enter the Email ID:xxxxxxxxxxxx
Enter whether your beginner or not:beginner
Enter the college name:Sumathi Reddy Institute of Technology for women
Enter the date of birth:22-09-2008
Enter the current location:Warangal
Enter the nationality:Indian
Enter the certificates gained:SIH participation certificate
Enter the medals obtained:Silver in Treasure Hunt
Select the design as per your reqiurement:
designs:
a)1-simple
b)2-moderate
c)3-high level
d)4-Extra high level
Enter the number:3
===============================================================
  RANGU KEERTHANA   
===============================================================

* PROFILE: Motivated B.Tech standard seeking an internship opportunities to apply programming knowledge in C,Java,Python,ehance problem-solving skills,and gain real-world industries experience

*EDUCATION
----------
college: Sumathi Reddy Institute of Technology for women

*TECHNICAL SKILLS
----------
Programming LANGUAGES:: C,Java,Python
Tools: VS code,Jupyter

KNOWN LANGUAGES: Telugu,Hindi,English

*ACHIVEMENTS
----------
Certificates: SIH participation certificate
Medals: Silver in Treasure Hunt

*CONTACT DETAILS
----------
contact Number::xxxxxxxxxxx
Email ID::xxxxxxxxxxxx

*PERSONAL DETAILS
------------
DATE OF BIRTH: 22-09-2008
LOCATION: Warangal
NATIONALITY: Indian
The above mentioned details are true
