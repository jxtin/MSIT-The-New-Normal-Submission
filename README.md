# CoBAND

## INTRODUCTION


**CoBAND** is a product idea developed by Team Ducks on Fire which aims to break down the COVID-19 crisis at the time of reopening of organizations like schools, colleges, offices etc to ensure the lasting safety from the novel coronavirus during the aftermath of the lockdown. The bands (nomenclated “CoBANDs”) would target to estimate the health and wellness of each and every individual on premises by continuously tracking four of their vitals : SPO2, heart rate, temperature and blood pressure. This will thus improvise the current system of recording solely temperatures at the entry checkpoints multi-folds and go on to ensure that any deviation from normal is recorded as a dynamic aggregate of the more diverse vitals throughout the time they are on premises. Once that is being done, alerts can be generated and requisite protocols can be ensured to escort potentially / actually COVID ridden people off-campus. We have currently deployed the software side, which includes both the website and the application using a randomly generated databse of 3 vitals for multiple students on the admin-side dashboard [https://coband19.jxt1n.repl.co/] as well as the mobile application for the student/employee side.


## Prototype

The prototype thus includes both a hardware and a software part developed through three versions to get to the final product. Our existing prototype versions have been explained with all their semantics in this report : https://docs.google.com/document/d/1xhUftrHGRukB2wiMmyU79MKb7XuntHSvzRcDs5I9J3w/edit?usp=sharing . The idea behind making multiple versions was to ensure that the developing hardware adds to the functionalities of the software end in a manner that would improvise on the existing product and allow for further scaling / improvements without rendering the mobile application / website for our product entirely dysfunctional. The future could see the development of the physical hardware further with the application and the website dashboard being intact.

The software includes admin side dashboard and client side dashboard. A python web flask is used to make the admin side dashboard. Flutter technology is used in the client side dashboard. Because of lack of direct hardware data fetching, the data for the dashboard is being fetched from Cloudant after uploading it from a remote device. The web site & client side app dashboard are dynamic in nature and are updated as new data is realised by the web / mobile app. Dynamic updating and health analytics make it easier for the user to understand. 

The final version's admin-side dashboard : https://coband19.jxt1n.repl.co/
The final version of the application has been deployed with this repository.