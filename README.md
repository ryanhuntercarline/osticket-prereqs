<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install/Enable IIS
- Install PHP Manager for IIS
- Install mySQL
- Extracting osTicket Contents to Web Server' Directory
- Complete Setup of osTicket on Virtual Machine

<h2>Installation Steps</h2>

<p>

![enableIIS](https://github.com/ryanhuntercarline/osticket-prereqs/assets/141659465/30009213-56f8-4d64-a1a8-4db167d1b405)

</p>
<p>
Installing/enabling IIS for osTicket is necessary as it provides the web server infrastructure required to host and serve the osTicket application on a Windows system. IIS handles HTTP requests, manages application pools, and processes PHP scripts, allowing users to access and interact with osTicket via a web browser. This setup ensures a reliable and secure platform for managing customer support inquiries and tickets.
</p>
<br />

<p>

![PHPManagerinstall](https://github.com/ryanhuntercarline/osticket-prereqs/assets/141659465/042f185d-ad14-4f2e-aae9-3af8144d2589)



</p>
<p>
Installing PHP Manager for IIS is beneficial when setting up osTicket because it simplifies the configuration of PHP settings on the IIS web server, ensuring optimal compatibility and performance for the osTicket application. The tool allows administrators to easily adjust PHP versions, modules, and error handling without manual configuration, streamlining the process of preparing the server environment for osTicket's PHP-based functionalities. This facilitates a smoother deployment and maintenance of osTicket on IIS, enhancing its responsiveness and user experience.
</p>
<br />

<p>

  ![mySQLinstall](https://github.com/ryanhuntercarline/osticket-prereqs/assets/141659465/1c530b8d-137a-49ed-818b-68c921f3d7a2)

</p>
<p>
Installing MySQL for osTicket is essential because osTicket requires a relational database to efficiently store and manage customer support tickets, user information, and other relevant data, ensuring seamless tracking and resolution of inquiries through its web-based interface. MySQL's capabilities in handling structured data, scalability, and support for concurrent access make it a suitable and reliable choice to power the backend of the osTicket application.
</p>
<br />

<p>

![osTicketextraction](https://github.com/ryanhuntercarline/osticket-prereqs/assets/141659465/106af2bd-f31c-4669-9257-65bb5bd578bc)

</p>
<p>
 Extracting the osTicket archive to your web server's directory is necessary to make the osTicket files and code accessible for installation and execution. By extracting the archive, you create the file structure and hierarchy needed for the web server to serve the osTicket application's web pages and functionalities to users who access it through a web browser.
  
</p>
<br />

<p>
  
![osTicketcomplete](https://github.com/ryanhuntercarline/osticket-prereqs/assets/141659465/3b42aef1-25dd-47c8-84bb-173e94b5406c)

</p>
<p>
  Downloading osTicket for practicing ticketing procedures allows you to create a controlled environment to simulate real-world customer support scenarios. By interacting with the application, you can learn how to effectively manage and respond to support tickets, understand the workflow, and develop your skills in handling customer inquiries and issues, all within a safe and isolated environment. This practical experience helps you become proficient in using osTicket before applying your knowledge in a live customer support setting.

</p>
