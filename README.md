# EX03-Enumeration
Enumeration Techniques

## Explore Google hacking and enumeration:

## AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.
Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com
## OUTPUT:
![image](https://github.com/user-attachments/assets/15e8cb3c-8d3a-4e4d-a435-8bc3402ebcde)

filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com
## OUTPUT:
![image](https://github.com/user-attachments/assets/0ed8371b-7f42-4b07-8d78-bb89483cb3ec)

intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
## OUTPUT:
![image](https://github.com/user-attachments/assets/46db54be-436a-4568-9168-9d668cedc849)



inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
## OUTPUT:

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
## OUTPUT:
![image](https://github.com/user-attachments/assets/63774bda-3619-4734-a694-c00b207f6656)


link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
## OUTPUT:
![image](https://github.com/user-attachments/assets/66da7068-52ec-42d0-89db-adb80c9ed8ad)


cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.
## OUTPUT:
![image](https://github.com/user-attachments/assets/aea3e564-06c8-4603-9436-c3b75d1b9058)

 
# DNS Enumeration:

## DNS Recon:
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:
![image](https://github.com/user-attachments/assets/a6fa0060-2978-452b-a3fa-fcd960c4b80e)
![image](https://github.com/user-attachments/assets/2a4af06c-fb35-4b04-b926-751aa0f2b795)


![image](https://github.com/user-attachments/assets/ee58dc14-f18b-4fed-a0f7-c6505fb4e8e3)


## smtp-user-enum:
![image](https://github.com/user-attachments/assets/b68cb66f-dc88-45f0-af23-0b0b27cbcd50)


## nmap –script smtp-enum-users.nse <hostname>:
![image](https://github.com/user-attachments/assets/7c7f46a1-7e6a-412c-a498-d4e5e4dd76ae)

  

## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully
