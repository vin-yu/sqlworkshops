![](graphics/microsoftlogo.png)

# Workshop: Machine Learning with SQL Server

#### <i>A Microsoft Course from the SQL Server team</i>

<p style="border-bottom: 1px solid lightgrey;"></p>

<img style="float: left; margin: 0px 15px 15px 0px;" src="./graphics/textbubble.png"> <h2>About this Workshop</h2>

Welcome to this Microsoft solutions workshop on *Machine Learning in SQL Server*. In this workshop, you'll learn how to use SQL Server (on-premises or in a SQL Server Virtual Machine) to implement a Data Science solution using Machine Learning. You'll do this using a complete process to implement your solution. 

The focus of this workshop is to understand how to create a machine learning solution completely within SQL Server.

You'll start by understanding the problem your organization wants to solve, collecting the data you need to solve problem, then creating an experiment, testing the experiment, and on to operationalizing the Machine Learning model - all with a focus on how to extrapolate what you have learned to create other solutions for your organization.

This README.MD file explains how the workshop is laid out, what you will learn, and the technologies you will use in this solution.

(You can view all of the [source files for this workshop on this github site, along with other workshops as well. Open this link in a new tab to find out more.](https://aka.ms/sqlworkshops)

<p style="border-bottom: 1px solid lightgrey;"></p>

<img style="float: left; margin: 0px 15px 15px 0px;" src="./graphics/checkmark.png"> <h3>Learning Objectives</h3>

In this workshop you'll learn:
<br>

- What Machine Learning is and what problems it solves
- The process for creating a Data Science solution
- How to configure and use Machine Learning Services in SQL Server
- How to call the predictions or classifications in SQL Server one at a time, or in a batch request mode

This Workshop uses SQL Server 2019 (although the instructions work with SQL Server 2017 as well), and uses Jupyter Notebooks in the Azure Data Studio tool to send commands in SQL, Python, R and Java to a SQL Server Instance to demonstrate an end-to-end soltuion using the Team Data Science Process.  

The goal of this workshop is to train data professionals to use Machine Learning in SQL Server for a secure on-premises, in-cloud, or hybrid approach to Data Science solutions.

The concepts and skills taught in this workshop form the starting points for:

    <TODO: Job Description and level of person who is the primary that should attend and the reason>.
    For instance: Solution Architects and Developers, to understand how to put together an end to end solution.
    <TODO: Job Description and level of person who is the secondary that should attend and the reason>.
    <TODO: Job Description and level of person who is the third-level of who might want to attend and the reason>.

<p style="border-bottom: 1px solid lightgrey;"></p>
<img style="float: left; margin: 0px 15px 15px 0px;" src="./graphics/building1.png"> <h2>Business Applications of this Workshop</h2>

Businesses require <TODO: Describe the reason the student's business or organization would be interested in the information. Be detailed about the solutions it addresses> 

Some industry examples of <TODO: Workshop Topic> are <TODO: Enter Sectors and use briefly>, to name just a few.

<p style="border-bottom: 1px solid lightgrey;"></p>

<img style="float: left; margin: 0px 15px 15px 0px;" src="./graphics/listcheck.png"> <h2>Technologies used in this Workshop</h2>

The solution includes the following technologies - although you are not limited to these, they form the basis of the workshop. At the end of the workshop you will learn how to extrapolate these components into other solutions. You will cover these at an overview level, with references to much deeper training provided.

 <table style="tr:nth-child(even) {background-color: #f2f2f2;}; text-align: left; display: table; border-collapse: collapse; border-spacing: 2px; border-color: gray;">

  <tr><th style="background-color: #1b20a1; color: white;">Technology</th> <th style="background-color: #1b20a1; color: white;">Description</th></tr>

  <tr><td><i>TODO: Technology name not owned by Microsoft that you will cover</i></td><td>TODO: Reason the student needs to learn it</td></tr>
  <tr><td>TODO: Technology name owned by Microsoft that you will cover</td><td>TODO: Reason the student needs to learn it</td></tr>

</table>

<p style="border-bottom: 1px solid lightgrey;"></p>

<img style="float: left; margin: 0px 15px 15px 0px;" src="./graphics/owl.png"> <h2>Before Taking this Workshop</h2>

You'll need a local system that you are able to install software on. The workshop demonstrations use Microsoft Windows as an operating system and all examples use Windows for the workshop. Optionally, you can use a Microsoft Azure Virtual Machine (VM) to install the software on and work with the solution.

You must have a Microsoft Azure account with the ability to create assets.

This workshop expects that you understand <TODO: Enter a brief solution for what a student should know before taking the workshop>.

If you are new to these, here are a few references you can complete prior to class:

<TODO: Enter some pre-work courses or books or whatever that the student could use to prep>
-  [Reference Name](https://url)
-  [Reference Name](https://url)
-  [Reference Name](https://url)
-  [Reference Name](https://url)


<img style="float: left; margin: 0px 15px 15px 0px;" src="./graphics/bulletlist.png"> <h3>Setup</h3>

<a href="url" target="_blank">A full pre-requisites document is located here</a>. These instructions should be completed before the workshop starts, since you will not have time to cover these in class. <i>Remember to turn off any Virtual Machines from the Azure Portal when not taking the class so that you do incur charges (shutting down the machine in the VM itself is not sufficient)</i>.

<p style="border-bottom: 1px solid lightgrey;"></p>

<img style="float: left; margin: 0px 15px 15px 0px;" src="./graphics/education1.png"> <h2>Workshop Details</h2>

This workshop uses <TODO: enter main technologies used to solve the sceanrio>, with a focus on <TODO: architecture and implementation, development and use, etc>.

<table style="tr:nth-child(even) {background-color: #f2f2f2;}; text-align: left; display: table; border-collapse: collapse; border-spacing: 5px; border-color: gray;">

  <tr><td style="background-color: Cornsilk; color: black; padding: 5px 5px;">Primary Audience:</td><td style="background-color: Cornsilk; color: black; padding: 5px 5px;">TODO: Enter the technical people who will take the workshop> tasked with TODO: Enter what they are tasked to do</td></tr>
  <tr><td>Secondary Audience:</td><td> TODO: Secondary Audience</td></tr>
  <tr><td style="background-color: Cornsilk; color: black; padding: 5px 5px;">Level: </td><td style="background-color: Cornsilk; color: black; padding: 5px 5px0;"> TODO: 100, 200, 300, 400 </td></tr>
  <tr><td>Type:</td><td>TODO: In-Person, On-Line, or from github</td></tr>
  <tr><td style="background-color: Cornsilk; color: black; padding: 5px 5px;">Length: </td><td style="background-color: Cornsilk; color: black; padding: 5px 5px;">TODO: Number of hours</td></tr>

</table>

<p style="border-bottom: 1px solid lightgrey;"></p>

<img style="float: left; margin: 0px 15px 15px 0px;" src="./graphics/pinmap.png"> <h2>Related Workshops</h2>

 - [Using Machine Learning Services in SQL Server with Java and Microsoft Azure Cognitive Services](https://github.com/amthomas46/SQL/tree/master/sql-cs-icc)

<p style="border-bottom: 1px solid lightgrey;"></p>

<img style="float: left; margin: 0px 15px 15px 0px;" src="./graphics/bookpencil.png"> <h2>Workshop Modules</h2>

This is a modular workshop, and in each section, you'll learn concepts, technologies and processes to help you complete the solution.

<table style="tr:nth-child(even) {background-color: #f2f2f2;}; text-align: left; display: table; border-collapse: collapse; border-spacing: 5px; border-color: gray;">

  <tr><td style="background-color: AliceBlue; color: black;"><b>Module</b></td><td style="background-color: AliceBlue; color: black;"><b>Topics</b></td></tr>

  <tr><td><a href="url" target="_blank">TODO: 01 - Module Name </a></td><td> TODO: Module Description</td></tr>
  <tr><td style="background-color: AliceBlue; color: black;"><a href="url" target="_blank">TODO: 02 - Module 2</a> </td><td td style="background-color: AliceBlue; color: black;"> TODO: Module Description</td></tr>
  <tr><td><a href="url" target="_blank">TODO: 03 - Module Name </a></td><td> TODO: Module Description</td></tr>
  <tr><td style="background-color: AliceBlue; color: black;"><a href="url" target="_blank">TODO: 04 - Module 2</a> </td><td td style="background-color: AliceBlue; color: black;"> TODO: Module Description</td></tr>  <tr><td><a href="url" target="_blank">TODO: 05 - Module Name </a></td><td> TODO: Module Description</td></tr>
  <tr><td style="background-color: AliceBlue; color: black;"><a href="url" target="_blank">TODO: 06 - Module 2</a> </td><td td style="background-color: AliceBlue; color: black;"> TODO: Module Description</td></tr>

</table>

<p style="border-bottom: 1px solid lightgrey;"></p>

<p><img style="float: left; margin: 0px 15px 15px 0px;" src="./graphics/geopin.png"><b>Next Steps</b></p>

Next, Continue to <a href="https://github.com/Microsoft/sqlworkshops/blob/master/SQLServerMLServices/00-Prerequisites.md" target="_blank"><i> Pre-Requisites</i></a>