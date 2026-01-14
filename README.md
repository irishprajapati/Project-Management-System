Project Management System
Functional requirements
1. Employee Management Module
i.	Employee Profile management 
•	Creating a new employee with basic information like full name, email, password, skills, position and department
i.	Accessible to Social media login(email, GitHub and Microsoft)
•	Access to upload a profile photo
•	Edit/Update existing profile details
•	View the employee list in the table format.
•	Employee login and logout will be traced(need to research)

ii.	Search and filter
•	For the information of employee searching by the (email, id, name or skills) under certain department
•	Use case: Employee searched with name “hari” or id 2 in the project folder to see the contributor for any purpose
•	Use case: Employee searched by testcase12@gmail.com to find the employee
•	Employee can view information by using filter by department, skills or availability 

iii.	Sorting and Pagination
•	Employee list will be sorted by joining date, name or skills on any certain project mainly based on alphabetic order
•	Use case: sorting the employee by newest first or alphabetically
•	For faster loading the pagination are done in employee list where 10 number of employee are only shown
iv.	Collaboration with other team members
•	Employee can collaborate with other employee at the conditions when another employee needs any review part of code, documentation and other.
•	Collaboration can be based on comment, description and file attachment on tasks of any employee which be seen as notification in assigned employee
•	Ensure that one project tasks can be accessible for same project assigned employee

v.	File attachment
•	File attachment can be made on project description from employee to mark some important topics such as changes related to project, documentation changes and status update of employee

vi.	Employee Schedule 
•	The availability, leave and working hours on project tasks by employee will be seen on table format

vii.	Department employee
•	Managing the list of employee with table format in same department to access information

viii.	Task review submission
•	While the submission of tasks completion the tasks status are changed to review by employee for the review by Project Manager
2. Project module
i.	CRUD Operations
•	Creation of project with the status marking and read, update, delete permissions for superuser
•	Functionality to store and manage project in database

ii.	Basic search & filtering
•	Implementation of search module can help to search the name or description of project which will help to locate the project more efficiently
•	Filtering project by department, status or priority

iii.	Sorting
•	Projects are sorted by the name, priority and deadline which helps to organize the list of project based on importance and urgency

iv.	Project Documents
•	Uploading a description of docs and files related to the project can help in resource allocation as all information are in one place of project

v.	Assign Employees
•	Assigning a employee as project manager/hr and other as employee to view who is responsible for project and what are other roles working on this project



vi.	Status tracking & progress
•	Project updates are required to know about tasks completion and what are left to be done so status like Todo, progress, review and completion are helpful for employees

vii.	Pagination
•	Breaking projects list into multiple pages can improve the readability and performance while loading

viii.	Auto-suggestion of employee(skills)
•	Assigning a employee in project can be more easier when the skills are sorted according to skills and filtering at top when assigning a employee

ix.	Calendar view of project
•	Project calendar that may include the deadline of tasks schedule and project start to end date with all necessary information will be shown here

x.	Project folder management
•	Project are managed in specific folder that can contain more projects inside of it
•	Use case: Development folder may include
i.	Website development
ii.	App development


3. Tasks Module
i.	Tasks CRUD
•	Tasks create, read, update and delete in project for basic function to manage the actual workflow
•	Tasks crud are performed by

ii.	File Attachments
•	Uploading the docs and tasks related images can provide more descriptive information 
iii.	Tasks comments 
•	Employee of the same workspace and project manager can review and write feedback about the tasks ongoing
•	Tasks comment are retrieved by the comment employee id/name and created and updated at.
•	Task comments can be made by HR/Project Manager and Admin

iv.	Basic search & filtering
•	In scalable projects, searching tasks using a title, description and tasks id can help to quicky allocate the specific tasks
•	Better tracking of tasks can be done by filtering status, priority and tasks

v.	Pagination 
•	Tasks are displayed in multiple pages to improve performance in large projects



vi.	Sorting
•	Organizing workspace in urgency as sorted by urgency, priority and deadline
•	Tasks can be sorted by creation date at first also.

vii.	Sub-tasks
•	Breaking a tasks module into sub-tasks to understand the module flow 
•	The sub tasks dashboard will be only seen by the employee who have created it limiting it to privacy of the tasks

viii.	Calendar view
•	Tasks may be assigned differently to each employee to keep that tasks flow will date and time the calendar view is required here
•	Use case aug11 – aug17 documentation and research part on the existing system, aug18 – aug28 resources allocation 

ix.	Tracking progress report 
•	Task tracking will help to discover the progress report of the employee
•	Task assigned to any employee and tasks completed at the end of deadline are necessary to generate a progress report
•	Tracking as todo, inprogress, completed, review

4. Notification Module
i.	Task assigned
•	Sending a notification to employee when a new tasks is assigned to ensure that employee is notified about responsibility over tasks. 
•	Use case: “You have been assigned a new tasks: API data correction”
•	Task assigned will be helpful when suggestion by skills like frontend or backend by skills

ii.	Deadline Reminder
•	Alerting employees about upcoming deadline on the tasks they are working on before 24 hours and 1 hour to prevent missing deadlines and help employee plan their next tasks efficiently

iii.	Comment & Mentions
•	Using @username and writing some description on tasks can sent a notification about the comment to keep informed of discussion related to they are involved in

iv.	Status change
•	Notifies the employee when the status of their tasks changes to update the project manager about the progress or delays in tasks/projects
•	Notification changed to review by employee will be notified about the submission change by employee

v.	Overdue alerts
•	This notification will be sent when a tasks deadline is passed without the tasks being completed to highlight delays and ensure timely follow up by employees


5. Admin module
i.	Dashboard overview
•	Shows the total number of employee with the descriptive information 
•	Shows active projects with the each assigned member and employee list 
•	Viewing pending tasks and tasks overdue in dashboard as table format

ii.	User Management
•	Add, update, delete or deactivate employee and managers
•	Admin will have control of system access and role assign
iii.	Project & Task oversight
•	Admin can manage the project and tasks if there is issue of delay or mismanagement 
•	Insights of project and tasks regardless of assigned roles

iv.	Roles & Permission management
•	Defining roles(Admin, project manager, developer, QA) and set module access
•	Ensures employee only view what they are allowed to

v.	Audit logs
•	Tacking features like:
i.	Tasks assigned
ii.	Status changes


6. Project Manager Module
i.	Employee Management 
•	Assigning to different employee according to their roles in department
•	Invitation to employee and manually adding the employee in workspace

ii.	Dashboard overview
•	Showing logistics about total running projects and total member in certain departments
•	Progress report of any department and any percentage


iii.	Documents management of employee
•	Keeping the track of employee with the documents related to personal details, NDA and other credentials

iv.	Documents Updating of project
•	Requirement of project documents like functional requirements, deadlines report and objectives related to developing the signature are kept in project to allocate resources

v.	Manage department details 
•	Project manager can manage department information and employee under certain departments

vi.	Roles and permission management
•	Project manager will provide the roles according to skills and department as who is responsible and who will take responsibility 
•	Roles can be considered as team lead, employee and other

vii.	User management
•	User management will be crucial as project management have to deal with user add update and delete in different department and different roles

viii.	Search filter & sorting
•	Project manager can search the project in overview dashboard and search by employee in the project folder
•	Sorting the tasks by alphabetic order of all project folders

ix.	Project & status oversight
•	Project are marked as the completion, pending and review by project manager 
•	Status that are changed into review by employee can be reviewed by project manager and completed if successful

x.	Audit logs
•	Audit logs are managed as:
a.	Status changed
b.	Task assigned 
c.	Overdue alerts
d.	Uncompleted tasks

xi.	Deadline reminders
•	Sending a deadline reminders to employee before 24 hours and last hour if the tasks is not completed
•	If the tasks are completed then deadline reminders are not sent

7. Human Resource
i.	Progress report
•	Viewing all the content of project how much progress have been made by the team are shown in dashboard
•	Team progress overview can be viewed
•	Shows the average tasks completion rate of departments

ii.	Dashboard overview
•	Showing logistics about total running projects and total member in certain departments
•	Project list overview and total member in each department can be viewed
•	Department breakdown and description as count of employees working on which project and completion rate
•	Recent activity feed like “Manish requested for leave, anish completed bug check task”

iii.	Documentation of company
•	Assigning each department the projects after consulting with project manager
•	Keeping the documentation like NDA, company contract and resource files
•	Keeping track of each employee personal details for future enhancements
•	Only hr and accessed employee can view the personal information
•	Audit logs information if edited and updated with time references

iv.	Project status
•	Project are approved after only
i.	All tasks are done
ii.	Documentation is completed
iii.	Final review is passed by project manager

v.	Reminders of events
•	Reminders about the events, targeted notifications are allowed to send by HR
•	Use case: All employee should send leave request by may 10
<img width="451" height="690" alt="image" src="https://github.com/user-attachments/assets/ed7cd6a7-25eb-41b6-887e-e6ae6ba441db" />
