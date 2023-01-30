# notes requirement
1. User should be able to create Notes
2. User should be able to read Notes
3. User should be able to update Notes
4. User should be able to delete Notes
5. User should be able to associate a status with note (e.g. Urgent, Important, Archived, etc)
6. User should be able to share note with specific users (By default notes are private)

///////////////Tables/////////////
1. note (id, title, detail, isArvchived)
2. user (id, name, emailid, user_name, password)
3. note_status (id, status) -> fixed values




//////Backend//////
Database - MySql
Tech stack: Spring Boot

//////Frontend/////
Tech stack: React JS


/////APIS//
Backend:
 createNote
 getNote
 getAllNotes
 updateNote
 deleteNote
 archiveNote
 shareNote
 makeNotePrivate
 
 
 createUser
 getUser
 deleteUser
 updateUser
 
 
