# Community_Cooperation_Covid-19
The main aim of this project is that community cooperation is critical in maintaining steady headspace and a calm environment during a panic.
############################################################################################################################
1.	Team Name – Team6
Team Leader’ name – Bhavana Innuguva
Team Leader’ email id – bhavana_winner@gmail.com
2.	Solution Brief Overview – 
Aim:
The main aim of this project is that community cooperation is critical in maintaining steady headspace and a calm environment during a panic; and its easier said than done. During such a crisis, it is imperative to help one another. Developing solution to assist in this area are integral in dealing with a pandemic.
What is the problem?
There is a growing interest in enabling communities to cooperate among themselves to solve problems in times of crisis, whether it is to advertise where supplies are held, help for collections, or provide other local services like volunteer deliveries. While governments may be rolling out broad programs, cooperation at the local level is usually the most effective way of getting help to where it is most needed. While traditional social media is one way of communicating within a community, this is (by its very design) not locally focused, and often not sufficiently structured to enable rapid discovery of what and where help is needed. With the COVID-19 crisis, we have already seen problems with the local supply of food, equipment, and other supplies.
How can technology help?
Mobile, web, and cloud services enable rapid deployment of applications that can empower cooperation in the community. Watson Assistant is a service on IBM Cloud that allows us to build, train, and deploy conversational interactions into any application, device, or channel. Creating a chatbot using Watson Assistant can help us address the issues that our users can face while trying to gather the necessary information. Embedding location/routing services (like these) can enhance such applications, giving optimum guidance so that they are outside of their isolation location for the minimum amount of time. 
3.	Working Model – https://youtu.be/L15xkrhd7Vc
4.	Solution description -
Scope of the project: The goal of this project is to provide a mobile application, along with server-side components, that serves as the basis for developers to build out a community cooperation application that addresses local needs for food, equipment, and resources. It would allow both "Suppliers" (such as a store or a community member who has produce they can sell or distribute) to make people aware of what they have; and consumers ("Recipients") to locate where these supplies are, and, if necessary, guide them to the appropriate locations to pick them up.
5.	Solution Architecture - This can include information on the business model, funding needs, and a sustainability plan.
Flow Diagram:
ARCHITECTURE OF THE PROJECT;
 
Aim: The main aim of this project is that community cooperation is critical in maintaining steady headspace and a calm environment during a panic; and its easier said than done. During such a crisis, it is imperative to help one another. Developing solution to assist in this area are integral in dealing with a pandemic
a.	The user visits a website with the COVID-19 chatbot and asks a question.
b.	The Node.js web server calls Watson Assistant hosted in IBM Cloud.
c.	Watson Assistant uses natural language understanding and machine learning to extract entities and intents of the user question.
d.	The Recipient user launches the mobile app and can access information across multiple services.
e.	The Recipient user can ask questions to Watson Assistant and get answers on food/service availability questions.
f.	The Supplier user can post the availability of resources they can provide, as well as locate the items they need.
g.	The Recipient user can obtain geolocation data to plot routes to collect (or drop off) supplies using HERE Location Services.
h.	IBM Cloud Function calls Watson Discovery running in IBM Cloud.
i.	Watson Discovery scans news articles and responds with relevant articles.
j.	IBM Cloud Function calls the COVID-19 API to get statistics.
k.	Watson Assistant replies to the user inquiry.
l.	The Node.js web server displays the chat answer to the user.
6.	IBM Cloud Services/Systems – List of one or more IBM Cloud Services or IBM Systems used in the solution
•	Watson Assistant
•	IBM Cloud Function
•	Node.js web server
•	Native APIs
•	IBM Watson Discovery
##############################################################################################################################
