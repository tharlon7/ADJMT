# **IS Development Methodologies – 31257 Autumn 2020 Project**

Tharlon Khinzaw – 98131535

Arvin Reyes – 13208323

David Nguyen ­– 13254800

Jannatul Naim Apon – 13122383

Mohammed Alvi – 12736195

Main body word count: 1993

#
## **Table of Contents**

[Executive summary 3](#_Toc41524599)

[Problem definition 4](#_Toc41524600)

[Objectives 4](#_Toc41524601)

[Stakeholders 4](#_Toc41524602)

[Empathy maps 5](#_Toc41524603)

[POV statements 9](#_Toc41524604)

[Travel Company Owner 9](#_Toc41524605)

[Relationship Managers 9](#_Toc41524606)

[Inbound End-customers 9](#_Toc41524607)

[Outbound End-Customers 9](#_Toc41524608)

[Design thinking approach 9](#_Toc41524609)

[Reflection 9](#_Toc41524610)

[Travel Company Owner 10](#_Toc41524611)

[Relationship Managers 10](#_Toc41524612)

[Inbound End-customers 10](#_Toc41524613)

[Outbound End-Customers 10](#_Toc41524614)

[Prioritised backlog 10](#_Toc41524615)

[Functional Requirements 10](#_Toc41524616)

[Non-functional Requirements 11](#_Toc41524617)

[User stories 11](#_Toc41524618)

[Work products, models, and descriptions 12](#_Toc41524619)

[Use case diagrams 12](#_Toc41524620)

[Activity diagrams 13](#_Toc41524621)

[Class diagram 15](#_Toc41524622)

[Collaborative diagram 15](#_Toc41524623)

[Competitive advantages and possible effects of project failure 16](#_Toc41524624)

[Competitive Advantages 16](#_Toc41524625)

[Possible Effects if the Project Fails 17](#_Toc41524626)

[References 18](#_Toc41524627)

#
## **Executive Summary**

A major travel company would like to develop an information system to improve the operation of its in-house call management centre (CMC). This report is divided into four distinct sections: 1. Problem Definition 2. Design Thinking Approach, 3. Work Products, Models, and Descriptions, and 4. Competitive Advantages and Possible Effects of Project Failure.

The report commences with the Problem Definition, which outlines the problems of the current system. This section also lists numerous objectives of the project, such as: increasing the number of sales of holiday packages and improving customer satisfaction. A list of stakeholders that will affect or be affected by the system is also conveyed. This section will also state the assumptions our team has made for the project. These assumptions are then used to create POV statements for each of the stakeholders involved, as well as empathy maps.

The second section of the report is Design Thinking Approach. This section contains a reflection which states further assumptions made for the project which include brainstormed ideas and the formation of HMW statements. A backlog is then created listing the functional and non-functional requirements for the new system as well as user stories for all the stakeholders.

The user stories are then used to create use cases in the Work Products, Models, and descriptions part of the report. The use cases are then implemented to create a use case diagram for the proposed system. This is then used to create an activity diagram. The activity diagram is then used to create class and collaboration diagram for the new system.

The report is concluded with the Competitive Advantages section. It outlines the possible competitive advantages that the Travel Company can obtain if the proposed system is successful. These include a more efficient allocation of resources and time, as well as increasing customer satisfaction which is integral for many businesses in contemporary society. This section also denotes several possible adverse effects if the project fails, namely the high cost involved with a project of this magnitude and the possibility of customers switching to another travel company if their needs are not satisfied.

#
## **Problem Definition**

The Relationship Managers (RMs) for a major travel company perform sales of holiday packages for their customers. However, the system operation is complicated by the varying number and nature of these holiday packages. Under the current system, call routing and flow control are also not adjusted to RMs skills and customers profiles, making the process of selling holiday packages inefficient.

## Objectives

1. Develop an information system to improve the operation of the major travel company&#39;s in-house call management centre (CMC).
2. For the outbound calls, the system will create a target list for each RM based on their skills and profile.
3. For inbound calls, the system will connect end-customers to RMs through matching techniques.
4. Increase the sales of holiday packages
5. Increase customer satisfaction
6. Increase RMs satisfaction

## Stakeholders

1. Travel Company Owner (client)
2. Relationship Managers
3. Inbound End-customers (Customers who call the travel company)
4. Outbound End-customers (Customers that the Relationship managers call)

## Empathy Maps

![Travel company owner](https://github.com/tharlon7/ADJMT/blob/master/Empathy%20maps/Travel%20company%20owner.png?raw=true)

**Relationship managers**

![](https://github.com/tharlon7/ADJMT/blob/master/Empathy%20maps/HD-empathy-map-for-RM.png?raw=true)

##

![](https://github.com/tharlon7/ADJMT/blob/master/Empathy%20maps/Inbound%20customer.png?raw=true)

![](https://github.com/tharlon7/ADJMT/blob/master/Empathy%20maps/Outbound%20customer.png?raw=true)

## POV Statements

### Travel Company Owner

**POV** : The travel company owner is missing out on increasing his company&#39;s profits, due to having an inefficient system for connecting his RMS to potential customers.

### Relationship Managers

**POV** : RMs, who are potentially missing sales opportunities, need to speak to the most suitable customers because they will be more likely to make a sale.

### Inbound End-customers

**POV** : Inbound end-customers, calling the travel company, are speaking to relationship managers, who are not the most suitable for satisfying their needs.

### Outbound End-Customers

**POV** : Outbound end-customers are receiving calls from RMS, who are suggesting them to purchase holiday packages that they have no interest in buying.

#
## **Design Thinking Approach**

## Reflection

The reflection outlines the assumptions and brainstormed ideas that our team has developed that were not made explicit in the assignment description. It is assumed that under the previous system, there are CMC telephone operatives who work under RMs. Their role is to take on customers calls and then depending on the nature of the call, direct the call to an appropriate RM if needed. It is also assumed that in the previous system, RMs have a database of numbers to make outbound calls from; however, they are cold calls to new potential customers. The functional requirements for the proposed system have been detailed in the project description and have been made clear by our team. However, non-functional requirements need to be assumed. The POV statements from the previous section are also used to assume How Might We (HMW) statements for each of the stakeholders involved. This is detailed below:

### Travel Company Owner

HMW Develop an information system to improve the operation of its in-house call management centre.

### Relationship Managers

HMW improve the process for RMs to connect with more appropriate potential customers

### Inbound End-customers

HMW match customers to the most suitable relationship managers

HMW reduce waiting times or delays for inbound customers

### Outbound End-Customers

HMW Direct calls from relationship managers to customers who are more likely to want to purchase holiday packages

HMW match appropriate Rms with the right skill-sets to outbound end-customers

## Backlog


### Functional Requirements

1. The system shall adjust the call flow rate to suitable RMs
2. The system shall match Rms and end-customers according to Rms skills and customer profiles
3. The system shall match customers based on RM performance and product knowledge
4. The system shall build a profile and skill matrix
5. The system shall adjust according to RMs subsequent performance in selling packages and in serving customers effectively and efficiently.
6. The system shall dial numbers automatically according to a customer target list generated by the system
7. The system shall retrieve customers details from a database
8. The system shall display the details and provides the RM with guidelines and a script to help in providing an improved service to the end-customer
9. For the outbound calls, the system shall create a target list for each RM based on their skills and profile.
10. For inbound calls, the system shall use a call routing and distribution routine to minimise inbound call costs.
11. The system shall calculate a skill score based on the RM&#39;s previous call duration and profile
12. The system shall use preloaded customer data to score inbound customers out of 10 based on their likelihood to purchase the product.
13. The system shall connect customers with the highest scores first with RMs
14. During busy times, the system shall direct inbound customers to an Interactive Voice Response unit prompting them for options, and ask for call reasons in a few words and then redirect the call to an Automatic Call Distributor routing the call to the first available appropriate RM

### Non-functional Requirements

1. The user interface for RMs shall be simple to use and easy to navigate through
2. Information that is entered by the RM shall be stored on a secured server
3. Navigating through customer profile pages shall load a display within 5 seconds at least 97% of the time
4. Every unsuccessful attempt by an RM to login to the system shall be recorded and after a third failed attempt the RM will be locked out from the system and will not be able to log in for another 3 hours.

## User Stories

- As a Travel Company Owner, I want the sales of holiday packages to increase So that the company&#39;s profits will increase
- As an inbound customer, I want to speak to the most suitable RMs, so that I can conveniently find the best value holiday package.
- As an inbound customer, I want to connect to an RM as fast as possible, so that I can be served promptly.
- As an outbound, I want to speak to the most suitable RMs So that I can have improved customer service.
- As a relationship manager, I want to connect with the most suitable customer, so that I can effectively meet the needs of the customer and make a sale.
- As a relationship manager, I want an interactive voice response system so that customers can get redirected once I am available to answer.
- As a relationship manager, I want to connect with customers easier so that I can find matching customers that are more willing to travel.

#
## **Work Products, Models, and Descriptions**

## Use Case Diagrams

#### Overall System:

![](https://github.com/tharlon7/ADJMT/blob/master/Folder%20for%20workproducts%20and%20models/Use%20case%20diagram%20%22inbound%20and%20outbound%22.png?raw=true)

## Activity Diagrams

#### For use case &quot;Call a customer&quot;:

![](https://github.com/tharlon7/ADJMT/blob/master/Folder%20for%20workproducts%20and%20models/Outbound%20customer%20Activity%20diagram%20by%20Arvin.png?raw=true)

#### For use case &quot;call travel company&quot;:

![](https://github.com/tharlon7/ADJMT/blob/master/Folder%20for%20workproducts%20and%20models/Use%20Case%20Diagram%20Inbound%20Customer.png?raw=true)

## Class Diagram

![](https://github.com/tharlon7/ADJMT/blob/master/Folder%20for%20workproducts%20and%20models/Class%20diagram%20final%20iteration%20by%20Arvin.png?raw=true)

## Collaborative diagram

![](https://github.com/tharlon7/ADJMT/blob/master/Folder%20for%20workproducts%20and%20models/Collaborative%20diagram%20Final%20iteration%20By%20Arvin.png?raw=true)

# **Competitive Advantages and Possible Effects of Project Failure**

## Competitive Advantages

The successful development of the proposed information system can result in numerous competitive advantages for the Travel Company. In targeting potential buyers with outbound calls, the proposed system will dial numbers automatically according to a customer target list generated by the system. The system retrieves customers' details from a database. It then displays the details and provides the RM with guidelines and a script to help in providing an improved service to the end-customer. As such, RMs can carry out more effective calls with a higher success rate of creating sales. This is much more effective when compared to cold-calling customers, which was the method used for the old system.
For Inbound calls under the proposed system, customers dial a number reaching the CMC which has its own private automatic branch exchange to route the calls. Due to this process, the Travel company can minimise inbound calls costs by reducing per-call handling time. For inbound calls, the proposed system will also serve customers with a higher score first and match them with the most appropriate RMs. This has two key benefits for the Travel Company. Firstly, RMs can increase their chance of selling holiday packages. Secondly, by matching the most suitable RMs to customers, the proposed system allows RMs to better service customer needs. Customer satisfaction is becoming increasingly crucial for businesses in contemporary society. During busy times, inbound customers under the proposed system can be directed to an Interactive Voice Response unit prompting them for options, and then direct the call to an Automatic Call Distributor routing the call to the first available appropriate RM.Through this, the Travel Company can further increase savings due to reduced staffing costs. With the new system, the previously assumed CMC telephone operative’s roles will now become automated, thus making them redundant.

## Possible Effects if the Project Fails

Although the proposed system has numerous potential advantages for the Travel Company, there can be very adverse effects if the project fails. Firstly, a system of this magnitude will be costly, and an appropriate budget and financial layout are necessary to make ends meet. 60-80% of all project failures can be directly attributed to poor requirements gathering, analysis, and management (Kaur & Sengupta, 2011). The requirements must be outlined correctly to prevent project failure. If the project fails due to an unrealistic schedule, i.e. too much work is crammed resulting in a less effective system, it can cause large problems for the Travel Company. If the project fails, customers may have preferred the old system and feel that their needs are not adequately satisfied by the Travel Company. This can lead to a negative image for the business and result in customers switching to another travel company. To prevent waiting until customers, complain or systems crash due to inadequate testing, it is imperative that proper testing during multiple phases of the project is conducted. Miscommunication between the RMs, Travel Company Owner and developers can also lead to project failure and more issues for the Travel Company. Furthermore, if the system is not properly implemented, RMs can have trouble adjusting to the new system, potentially decreasing the amount of holiday package sales. 
 

#
## **References**

Anon, n.d., Study.com. viewed 28 May 2020, <https://study.com/academy/lesson/what-is-a-use-case-definition-examples.html>.

explainagile.com 2019, explainagile.com. viewed 28 May 2020, <https://explainagile.com/blog/your-developers-are-stakeholders/>.

Kaur, R., Dr Sengupta, J. 2011, ‘Software Process Models and Analysis on Failure of Software Development Projects’, International Journal of Scientific & Engineering Research, vol.2, issue 2, pp. 3

UML, S. 2016, System Stakeholders - SYSTEM ANALYSIS AND DESIGN WITH UML, Studentstechlife.blogspot.com. viewed 28 May 2020, <https://studentstechlife.blogspot.com/2016/11/system-stakeholders-system-analysis-and.html>.

What is a Backlog? | Definition, Overview, and Purpose n.d., Productplan.com. viewed 28 May 2020, <https://www.productplan.com/glossary/backlog/>.
