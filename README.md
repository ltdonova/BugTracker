# BugTracker

Summary of Role:
This application is for ticket management for a project. Users can create projects and create tickets for the project to address the planning and development of a project. 
There are a variety of tickets such as issues, bugs, notes, etc. There is also mulitple types of users such as admins, project managers, developers etc with their own capabilities. The tickets should will have states that can set to describe their states in development. 


Role Types (User = root role) :
Admin: can see all projects, all CRUD capabilities for users/projects. 
Project Manager: can CRUD their projects, can assign/add people to projects 

User Type Hierarchy: 

User
    This is the base role that all other roles inherit from. Contains basic things like name, email. username, paasword etc.
Admin/Account
    Admin: can manipulate all users/projects (CRUD operations)
    Account: can only manipulate their own projects and that capability be limited based off of project role (below)
    
Project Roles:

Project Manager / Developer (these are the project roles) **** needs to be refined ******
    Project Manager: can do all CRUD operations to their projects and  can assign/remove people to their project. Can also do all other project role capabilities.
    Developer: can create tickets in a projects 

Ticket Types:

Task/Note/Issue/Bug **** will be refined *****

  Task: something to-do
  Note: Broad comment 
  Issue: problem 
  Bug: technical problem
  
  

