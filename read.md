# Knowledge 2019


## Keynote - Day 1

**Next Releases**

~~~
1. NewYork - 2019 Q3
2. Orlando - 2020 Q1
3. Paris - 2020 Q3
~~~

It's the time for Upgrade ...  

The interesting part here is , ServiceNow upgrade team has come with the release cycle called `Upgrade as a Service`, and customer can get the release before 60 days prior to Major release , so that they can test it in Pre-prod instances and feel confident for Upgrade in Prod.

**Improved versions of**

1. Automated Test framework for ServiceCatalog , ServciePortal, Forms
2. Lots of regression testing for their product

Beginning Madrid release , mobile platform is integrated with now platform. So now we can build any application .

**Guided App Creator**
Guided App Creator Module that helps us to create Applications

1. Import from exel and create tables  - spreadsheet to table converter
2. create web/mobileapplication in few minutes using Guided app Creator

**Integration Hub, Action Designer**

Provides integration user interface, so that we can easily integrate ServiceNow with other systems. Integration hub is already available in ServiceNow , and ServiceNow will be publishing the integrations with most of the system in upcoming releases.

So interestingly **Coupa** is one of them .
The concept of integrate ServiceNow with anything will be availble in NewYork Release.

**Incident Management - Agent workspace**

**ServiceNow** has come up with new feature called `virtual agent` which uses supervised machine learning to learn about the incidents and they assist while solving the similar incidents.

So basically that means using historical data , agent proposes the solution.

**Customer Workflow**

Improved version of Incident management : It was cool to see that people can speak to mobile app about incident and it assists you .

Demo on Onboarding mobile application was good .


**Finance Operation management- NewYork Release**

Definitely a lovable part for Sudeepa and Nikita is Month End.

Eventhough I couldn't understand properly as there was no demo , this module includes

1. Automated Journal entries
2. Integartion with SAP and Oracle
3. Embedded policy and Compliance


## Keynote - Day 2

**Artifiacial Inteliigence**
Supervised and Unsupervised learning , where system assists

~~~
Ex: for new issue, It may suggest that " I have observed that from historical data we have 20 similar cases and these are the 5 differnet way your team solved the issue and out of them this particular solution has been used for 80% of the cases .
~~~

"Automation takes us beyond the tickets"

Further, the most of the session was on Change management :  
Challenges like silo knowledge , manual process ,lack of visibility - So `Change Management` for devops is much needed process .

So we know we don't use change management in ThoughtWorks .

But I will try to expalin with an Example: So when Developers make cahnges and push to github, information flows to ServiceNow ,change request raised and it has to be approved .

And same goes with Employee workflow :

**Ticket Spin Cycle**

Workspace team deals with many tickets per day , but we all know most of them are same and we have to resolve the same issue most of the times. What if we automate this, Meaning without raising a ticket employees can solve their issue quickly.  

Virtual agent helps us to achieve this .


**Global workspace - Natural Language understanding : NewYork Release**

As a global company , we have to support multilple languages . Most of the time ticket raised in chinese language keeps in the system till next day waiting for the particular region team resolve the issue.

ServiceNow has the solution : Dynamic tranlation in English , smart and cool **Virtual agent** that understands us translates in english ansd help us to solve the ticket.



## Keynote - Day 3 - Available in NewYork and upcoming releases.

So whatever we heard in day 1 and day 2 ... Most of the keynote demos were on Mobile platform  and Virtual agent.

1. ServiceNow integrated with Siri shortcuts.
2. Speech recognition capabilities in native mobile app .
3. Generating the database query from unstructured text - virtual agents can just helps us to create reports

So Native App that listens , converts to text and understand using AI technology

Let's see how it works in detail:

Algorithm that devides the text into two parts :  For this we have to train the model

1. Intent: action that user wants to do.
2. Entity: Context for the action


Chatbot : Embedded in mobile app

**Some more points that are good to know:**  

1. ServiceNow runs over 5 million tests executing everyday.
2. ServiceNow is supporting multiple Prod instances if company needs.


Now comes the privacy, ServcieNow is working on  data protection , encryption , Key management :

Data resedency and Compliance : like GDPR ,to mainatain our data.  

Database encrytion product : Its a paid Model

##Sessions

I got a chance to attend some sessions after KeyNote like CI/CD session ,Software asset management using SAM pro , Automated asset management , Best practices for ServiceNow Upgrade,creating a global modern end-user focused self-service portal , Pick three: fast, reliable, cheap (an ATF story from Harvard Business School),Implementing 4 languages in the MetLife ServiceNow Platform .


**CI/CD Session by Swiss Re:**


1. The demo was on CI/CD , how to use CI/CD server in combination with tools like Bamboo or GitLab.  
2. so there are 8 developer instances and 35 developers . (I think I remember it correctly).
3. They have many scoped application , as we all know scoped application do support version control.
4.  I got a chance to talk with the tech lead **Rajiv from Swiss Re** and asked about Global app, he said it is possible to implement CI/CD and suggested to llok at opensource .

Here is the link to Opensource , please refer to this

1. [Clone example Project](https://github.com/bmoers/sn-cicd-example-v3)
2. [The CI/CD integration application](https://github.com/bmoers/sn-cicd-integration)
3. [To contribute to Project](https://github.com/bmoers/sn-cicd)

I have uploaded some pictures of the slides please have a look at the drive [here](https://drive.google.com/drive/u/0/folders/11rTdFjm-jrjNtp5OgTeP5xErUa7n0GCu)



**Software Asset Management using SAM Pro by CenterPoint Energy:**

I was surpised as there were no demos on SAM in KeyNote , but got a chance to attend this session.

I think we were also on the same boat as CenterPoint was on , they shared the similar issues that I heard from SLAM team like Financially risky compliance audits , inaccurate forecasting ,lack of control .

And also the journey of SAM  and journey to SAM maturity:

First step was to upgrade to Madrid , Portal integration with SAP and adobe. I have like 2 ppics from the slides, Please refer [here](https://drive.google.com/drive/u/0/folders/11rTdFjm-jrjNtp5OgTeP5xErUa7n0GCu)


**Automated Asset Management by PayPal+Deloitte:**

I was so exicted to attend this session to know what automation they have implemented like how we have achieved this through SMDM integration .

Deloitte's partenership with Paypal on the serviceNow Journey , for 3+ years . They have implemented many modules like DCIM , Servcice catalog request, Hardware asset management, Knowledge management , onboarding, Facility management , test management and more...

My concentration was on hardware asset management - **Packaged automated asset management solution** using AMS -Asset Management Sensors and RFID technolgy .

They also showed the demo by placing some assets with asset tags and passing through RFID gate and that capotures the data and uploads to ServiceNow .

Please find the pictures of slides [here](https://drive.google.com/drive/u/0/folders/1ERew9hqNx9bZcJj9N8jd4IeaSU40YqHg) for more information .


**Best Practices for ServiceNow Upgrades by ServiceNow**

It was a lab session where they created dev instances to all the attendees and they have upgraded all the instances , and session was to resolve the issues and run ATF after resolving the issues .

So ATF - Automated testing Framework plays very important role .

Steps were like :  

1. Prepare to upgrade the production Instance - Profile the performance of the instance specially in integration , instance performances. Document the same using ServiceNow Performance home page.
2. Run Automated test using ATF to confirm everything works as expected .

They also provide some courses on ATF , [Here is the link](https://servicenow.sabacloud.com/Saba/Web_spf/NA1PRD0015/common/ledetail/cours000000000024605)


**Creating a Global Modern End-user Focused Self-service Portal by lululemon:**

lululemon is a Canadian athletic apparel retailer . They shared the journey of designing self portal for their customers starting from user research .

I couldn't take any pictures, If they share some slides, will definitely going to share with you all .

It almost looked like out of box portal with little customization .

**Pick Three: Fast, Reliable, Cheap (an ATF story from Harvard Business School)**

Yes ......

This is my favorite session and the coolest session . The session was lead by 2 senior Quality analyst and  a developer .

Solution for all problems, issues..

1. Manuall test suites, delayed delivery of new value to customers , during each cycle executing acceptance and regression tests manually, so Quality is reduced .
2. They have created  a series of automated test suites for unit and regression testing .  

~~~
Summary :  By implementing ATF , they reduced the testing time from 7.5 days to 28 minutes for 281 test cases , they run test each day and monitor the test results and...and....Guess what Upgrade time reduced from 40 days to 10 days .
~~~

They have given some instruction to maintain ATF testcases, naming convention etc.

Okay , I know that you are waiting for more information on this , I have uploaded all the slides pictures in drive [Automated Test Framework](https://drive.google.com/drive/u/0/folders/1AvDHf3Az9JUU6pLtNqGZzBAk6e2yug5N)


**Implementing 4 languages in the MetLife ServiceNow Platform by MetLife**

Metlife tried to bring ServiceNow Platform to global employees across 44 countries and 4 languages. They have implemented i18n- Internatinalization  in ServiceNow platform for Japanese, Chinese, Spanish **partnered  with Infosys**

There goal was to translate many areas like incident,catalog items ,CMDB forms, text in Business rules , UI scripts, Script includes.

OOB plugins are available , but that doesn't allow us to tranlate many areas in platform.
Example Plugins are : i18N:French Translation ,i18N: internationalization etc

In some areas , Metlife team has added manual translation like email notificatrion, form customization, text in UI pages. They have also used load dsata module to import tranlations to tranlation table .

For more3 information on recommendations, challenges they faced , please refer to the slide pictures [Implementing 4 languages in Metlife](https://drive.google.com/drive/u/0/folders/1NWZbQGdxnkWP2Np26jLfgG_rAbIlr_i3)


##Some More

There were 20k people in the conference from all over the Globe.  

1. Some of them are using ServiceNow from 4 to 5 years and have implemented most of the modules in ServiceNow.
2. Some of them have just started with ServiceNow with baby steps like us
3. Some of them were there to learn how they can utilize the ServiceNow platform to their business .

All kinds of companies from medical, Software companies , Government sectors, and Airline are using ServiceNow either for customer workflow or employee workflow or IT workflow etc.

I got a chance to talk with some ServiceNow developers regarding Global and Scoped appliaction, the answer was its better to use Scoped application as upgrades are easy , and we can build the system as we want from scratch , and version control is available.


And also there were some cases when I felt to come out of sessions as they were all same , attended some lab session like upgrades , attended some creatorcon where people will explain about modules in serviceNow and we can dicuss with ServiceNow Developers.



Thank you
