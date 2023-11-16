# IoT-Based Faculty Managing System using Raspberry Pi and Time Activated Power Saving Monitor
A faculty managing system is used to track the attendance of the professors as well as the convenience for the students in knowing their consultation time. In our system, Internet of Things is implemented wherein professors can communicate outside the school/university.

## Introduction
Students who looks for professors happens inevitably. Students don’t know their whereabouts, one option they have is to look for the schedule posted outside the EECE Department, however, if they are not found in the room of their respective class or don’t have a class at that time, the only option left for students is to ask for them in the EECE Department. Doing that leads to disruption of faculty members who are busy doing their work. Sometimes, they don’t even find the answer even if they ask. The researchers are addressing to the problems of knowing if a faculty member is in the campus through the development of the research “IOT Based Faculty Managing System using Raspberry Pi with Distance and Time Activated Power Saving Monitor”.

A similar research made use of software database architecture uses MySQL for web-based, and SQLite for mobile applications. The system includes different modules that capture daily attendance of faculty members, generate faculty attendance reports and analytics, absences notification system for faculty members, chairperson and dean regarding absences, and immediate communication system concerning the absences incurred. However, the software database that they have used is only for local database, which means that it is not online, and the data is only stored in an SD card, so if the SD card corrupts, all data will be gone and can’t be retrieved. With our project, we have used firebase which is an online database. Data is persisted locally, and even while offline, Realtime events continue to fire, giving the end user a responsive experience. When the device regains connection, the Realtime Database synchronizes the local data, changes with the remote updates that occurred while the client was offline, merging any conflicts automatically. Moreover, the data can be shared to other systems.

This project focused on the development of an application that aids the university administrators to establish an efficient and effective system in managing faculty attendance. The idea of this project is to record the daily attendance of faculty members with the exact time in and time out for students to know whether the professor is inside the campus or not. Other interactive feature is added to the application, like announcement for a specific section of a course they’re handling or for the whole students under EECE department. The time in and time out function is only accessible through the monitor, along with that, they also have the option to posts remarks. An Android application was also made using an Appy builder in order for the faculty members to make some announcement wherever and whenever they want. The GUI software was made using the PyQT, and for the mobile Android application, Appy builder was used. All data is stored securely on a Firebase server managed by the administrator and ensures highest possible level of security.

The main objective of this research is to design and implement a faculty managing system. Specifically, this research aims to (1) make a responsive GUI for the attendance, announcements and faculty database using PyQt; (2) create an Android application that enables faculty members to post remarks; (3) make a database responsible for exporting and importing data in the cloud; (4) test the reliability of the app if the remarks sent is updated in the GUI; test the system’s range detection accuracy.

The system utilizes user authentication, displaying only information necessary for an individual’s duties. Also, the system has security and a level of integrity maintained that allows only authorized users to create or update their information in the system. Additionally, each sub-system has authentication allowing authorized users to create or update information in that sub-system. There is also a student user interface, allowing students to access information that is addressed to their corresponding courses. With the ultrasonic sensor and relay module, it gives the system power saving capability.

This design project focuses mainly on the software inside the raspberry pi, in which that software is used to monitor the attendance of faculty members and to give them an option to make an announcement. For the mobile application that was made for faculty members to post remarks, an internet connection is needed for it to be accessed, moreover, it is only limited to phones that has an Android operating system.

## Methodology
### Functions Performed by the Users
The user of this software will be the administrator, the dean of the department, subject chairpersons, faculty members and the students. Every user mentioned above, except the students, will have to register their name, provide a password, and indicate which department they belong for that information to be stored in the database. After the registration, an ID would be given to them automatically, this gives each user uniqueness in the case they have a similar name to someone. This system will satisfy the goal of centralized monitoring of the faculty members’ attendance and will be highly reliable. It will automate the manual work of students asking questions inside the EECE Department and faculty members answering their questions whether a professor is around the campus or not.

#### Administrator
There will be an administrator, the secretary of the EECE Department, who will be given all rights to access each detail related to the software and the database. This system has Administrator which is at the topmost level with all possible rights.

1. The only person who can access the Database Interface
2. The only person who can register a new faculty to the system
3. The only person who can access the Edit Interface, if a faculty member wants to edit his name or password, they need to contact the Administrator
4. The only person who can edit the time in and time out of the faculty members
5. Can make announcement that can be viewed by all; the one that can be seen in the Announce Interface

#### Faculty Members
Faculty has limited access to the system as per their designation. Faculty members will be given a username and password provided by the administrator for them to access the Faculty Interface. Unauthorized access is denied.

On Successful Login:

1. They can time in and time out for attendance purposes
1. They can post a remark for a specific course/section they are handling
1. Can view Attendance Interface
1. Can view Announce Interface

In Addition:

Faculty members who have mobile phones that have an Android operating system can use the application made to post remarks at their convenience.

#### Students
1. Can view the Attendance Interface
1. Can access the Student Interface to check if their professors have some announcement
1. Can view the Announce Interface

## Conclusion
Upon the completion of the study, the researchers were able to make a faculty managing system via IoT. The RPi, a microcomputer was used as a core component of the system. We were able to make a database in the cloud, in which it can import and export data through the GUI. Furthermore, the researchers were able to make an Android mobile application in which the user can make an announcement and that it will appear on the GUI. Moreover, our system has a power saving capability in which we made use of an ultrasonic sensor.

Also, the researchers tested the range detection accuracy of the ultrasonic sensor. The obtained result shows that it agrees with the expected outcome.

Lastly, the researchers tested the reliability of the data transmission of the Android mobile application to the GUI via IoT. Based on the obtained result, we can say that the data was transmitted accurately

## Recommendation
In order to improve the study much further, the researchers recommend making an application that can be used by IOS users, because the application we made is only accessible for devices that has an Android Operating System. The researchers also recommend making use of touch screen monitor instead, to lessen the hardware used.

## References
[1] ISO 10014:2006 Quality Management – Guidelines for realizing financial and economic benefits. – International standard. Retrieved from http://www.iso.org/iso/catalogue_detail.<br>
[2] Hesham Magd and Adrienne Curry, TQM in Egypt: a case study, An empirical analysis of management attitudes towards ISO 9001:2000 in Egypt, The TQM Magazine, Volume 15 · Number 6 · 2003 · pp. 381-390<br>
[3] Walid Zaramdini, An empirical study of the motives and benefits of ISO 9000 certification: the UAE experience, International Journal of Quality &Reliability Management, Vol. 24 No. 5, 2007 pp. 472-491. Retrieved from http://www.ukessays.com/essays/management/literaturereview-about-management-information-systemsmanagement-essay.php.<br>
[4] S. R. Bharamagoudar, Geeta R.B.2, S. G. Totad Assistant Professor, Dept. of Electronics & Communication Engg, Basaveshwar Engg. College, Bagalkot, Karnataka1Associate professor, Department of IT, GMR Institute of Technology, RAJAM, Andhra Pradesh2Professor, Department of Computer Science & Engineering, GMR Institute of Technology, RAJAM, Andhra Pradesh 3.<br>

## Tip
**If you like my hard work, I would appreciate it if you could buy some coffee for me.**

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/frosteen)