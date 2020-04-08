Model of Organization - To Be

# Summary of changes

The big issue of AS-IS system is that each section such as financial units, sales units, and other sections which are described before, just contact each other in a very inefficient way, like a telephone to do their tasks. Another problem which can cause the handling the warehousing process makes more complex is not having an integrated system to collect information from various sections. By doing so, accessing info could be extremely straightforward for each part and definitely in the long term, it would increase customer satisfaction.</br>

After the company experienced a lot of mentioned problems concerning to utilizing traditional approaches, they would decide to have the integrated central system. 
As a result of this, firstly, all of the dedicated and separated applications and local databases would be removed (all data would be preserved in temporary backup-drive ).</br>

Secondly, for the preparation of a central system app, we have 2 options, one of them is to buy from external vendors or develop the application internally which can cover all the company's needs with web-interface to interact .According to the company's policies and prospective, the application would be developed internally by the company's new team that is going to be hired. </br>

Thirdly, new infrastructures would be implemented and enhanced like to having server room and network cabling and all needed hardware.</br>

After these steps,we are going to see some effects and improvements on the company's processes in different departments like sales unit and warehousing,etc.

# Organizational variables
No changes
<!-- Keep this section and subsections, if there is no change just write "no change". In case there is a change detail it. -->

## Size

## Products services

## Goal, goal type, vision, mission, strategy

## Culture

## Structure

### IT office

## Formalization specialization centralization

## Organizational type

# Business model canvas

No Changes

# IS Views

## Functional view, data
<img src="https://www.mediafire.com/convkey/fe16/xgwve72lc75h7836g.jpg" alt="TO-BE"></img>

## Functional view, processes

Write no change if the model remains as in As Is

### Process selection

<!-- Report the PICK chart (see process redesign chapter) used to select the process to be changed and argument about it -->

### Process (PROCESSING THE REQUEST)

<img src="https://www.mediafire.com/convkey/df31/uoqqsu6cxivtogb6g.jpg" alt=""> <br>

<!-- For each changed process report the new BPMN (highlight where are the changes and why) and  the software functions needed by the IS, as follows -->

| Activity in BPMN | Supporting Software functions |
| --- | --- |
|  Checking the Availability   |  with integration system sales unit can access to the all list of available items in the warehouse and able to decide which departments should be take action.   |

### Process (RETURNING)
<img src="https://www.mediafire.com/convkey/1263/5rb983gpg7midjg6g.jpg" alt=""> <br>

<!-- For each changed process report the new BPMN (highlight where are the changes and why) and  the software functions needed by the IS, as follows -->

| Activity in BPMN | Supporting Software functions |
| --- | --- |
|making decision about request  |  all negotiations about request are transmitting over the system without any paper working |


## IT view

### Application portfolio

<!-- Write no change if the portfolio remains as in As Is

Otherwise list here the new portfolio, highlighting new applications, and abandoned applications. -->
There is a developed internally integrated central app with multiple functions which is providing the web interface access to all departments and providing the services that they need instead of separately using different vendor's app for each department.

#### Selection

Describe the applications considered for the selection

| Application name | Vendor | Description | Price model and fees |
| --- | --- | --- | --- |
|  Broonz-CentralApp |  Internally |  Main application with lot functionalities like automation and finance. |  hiring the developers and paying the monthly salaries |
|  Arian APP |  Arian System |  Business integrated system offered different applications and services such as ERP ,CRM ,billing, warehousing, etc. |  Suitable for all sizes company,Fees is medium |
|  Segal APP |  Segalpardaz |  Segal app is a business management software including marketing, financial, warehousing, reporting, etc. | Suitable for all sizes company,Fees is medium |
|  Odoo APP |   Odoo |  business management software including inventory,manufacturing, project management, billing, CRM, etc. |  Suitable for all sizes company,Fees is high |


Describe here how the selection of the new application was made

| Criterion | Broonz-CentralApp | Arian APP | Segal APP | Odoo |
| --- | --- | --- | --- | ---|
|  Integrity |  9 |  8 |  8 | 9|
|  Price | 10  | 8  |  7 |5|
|  Easily operated | 7  |  6 | 7  |9|
|  Support |  10 |  8 |  7 | 6|
|  Services | 10  |  7 |  7 |10|
|  Customization | 10 |  6 | 5  | 8|

BEST = 10, WORST = 0
<!-- Alternatively argue that the new application should be developed custom for the company. -->
According to the above comparison table, despite Odoo's functionalities and services, the price was too high and the support was not provided. so the decision has been made to develop the app internally inside the company.

#### Coverage

Show how the selected application provides the software functions needed (as identified in Functional view, processes section), discuss gaps, if any

| Software function needed (from process view) | Software function provided by application selected | Gap analysis |
| --- | --- | --- |
| Easy to Communicate through all departments  |  web-base application |  No |
|  Accounting | Invoice System  |  No |
| Inventory management and warehousing  |  web-base applicaiton | No  |
| Reporting and statistics |  web-base applicaiton | No  |


### Technological view

<img src="https://www.mediafire.com/convkey/7f95/ol04wdtrt1d0yfb6g.jpg" alt=""> <br>
<!-- Write no change in case. Otherwise report the new deployment diagram and highlight the changes -->

#### Integration

In case a new application is introduced discuss how integration happens in terms of:

<!-- * Data exchange (which data is exchanged)


* Control mechanism (mechanism used by applications to interact, ex message passing, rpc, etc) -->
All data and information are stored in a central database that easily transferred from local databases into central ones because the application has a web interface all departments can access it easily and communicate and exchange the information via the network.

# IT strategy

<!-- Discuss if there should be changes to it. -->

Now, the company is offered a new integrated system for all its departments by IT. The Central app has a lot of functionality and automation's abilities that covers all departments needs and integrity. So each department has to access those required functionalities via web-interface, therefore we have to categorize the departments and their employees into the different groups by declaration the username and password and using like the AAA server or Microsoft active directory to control the policies.</br>
Additionally, we have to concern about our servers and networks to be updated and secured and to be high availability. and then we have to make the backup of all data in databases periodically to use them in case of emergency and reduce the redundant data and for analyzing to make future decisions.</br>
Moreover, adding the more new modules and functions to the program based on new requirements.



# Effect of change(s)

1-Increased customer satisfaction.</br>
2-Great Useability and functionality </br>
3-Reduced ERRORS and lost</br>
4-Reduced Overhead-cost and time</br>
5-Reduced the production's time and improved the quality</br>
6-Integrity and seamless data </br>
7-Modularities and flexibilities to the needs.</br>
8-Reduce data redundants.</br>
9-Troubleshooting the problems and getting the support easily.</br>
10-Improved the security for data and whole systems and devices.</br>
11-Access to data and analyze them easily to make future decisions.(BI)</br>



## Effect on KPIs and CSFs

(remark, KPIs and CSFs should not depend on the change, but should remain the ones defined in the As Is section - the goal being to compare the effect of the change on the same indicators)

Report only indicators that are supposed to change, argument on why the change has an effect on them, report how much the indicator could change. Do not forget the unit cost of the product / service.

| Indicator (Csf, Kpi) name | Effect | Quantitative estimate of variation (absolute, %) |
| --- | --- | --- |
| S-LT0	  | Could be reduced  |  30% |
|  UC-0 |  Number of employees are reduced and there is no any paper/ink cost  | 25%  |
|   S-LTR0| Could be reduced   | 45%  |
|  UCR-0 | Number of employees are reduced and there is no any paper/ink cost   |  30% |

## TCO, ROI and Break even

Define the TCO for the change (use a 3 -5 years horizon)

Estimate costs (from TCO) and savings, and discuss the number of years needed to recover the investment

| Phase  | Cost | 
| --- | --- | 
| Construction  | Define requirements for new IT application,develop or acquire it|   
|  Deployment| Deployment of new IT application, training of employees|   
| Operation |  Electricity, conditioning |   
| Maintenace  | Fix of defects, development of new or enhanced functions  |   
| Dismissal  |  Transfer data into new systems |   

TCO = C+D + 5OM ,
TCOper year = TCO/5 

| Year/Cost or saving  | YEAR1 | YEAR2 | YEAR3 | YEAR4 | YEAR5 | 
| --- | --- | --- | --- | --- | ---|
|  Cost |  C,D |   |  |  |  |
|  Cost |  O,M |  O,M | O,M | O,M | O,M |
|  Saving | S  |   |  |  |  |

## Risks

Discuss the main risks (technological, organizational, human factors) related to the change, and what can be done to reduce them

Concerning human factors, it is essential to train all of employees to use the system precisely, beside of that compatibility could be reduced with other vendor's applications. 

# Conclusion

<!-- In summary, why the organization should buy (and pay for) your proposal of change? -->
In conclusion, based on analyzing the existing infrastructure, the company does not receive efficient outcomes and impressive effects on its operation because they are using old fashion and non-compatible applications without any good support and flexibility.</br>
As mentioned before according to the lack of integrity and communication and using separated and different vendor's apps which leads to having a poor performance of co-operation, having a lot of Errors and failures and a bunch of paper works and data lost.</br>
That's why the existence of perfect and widespread application in the company is necessary.
