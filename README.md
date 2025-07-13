
# JavaFX Customer Service Ticketing System for Sec4 of Advanced programming

 This is a desktop-based customer service application built with JavaFX.

---
## Features

- JavaFX GUI-based Interface
- FontAwesome Iconography for UI
- Role-based Access
- Admin, Agent, and Customer role support
- Data saved to '.txt' files (simple file-based storage)

---

## Project Structure

src/
└── main/
    ├── java/
    │   └── apassignment/
    │       ├── dashboard/
    │       │   └── DashboardController.java
    │       ├── ticketingsystem/
    │       │   ├── newTicketController.java
    │       │   ├── TicketController.java
    │       │   ├── TicketDetailController.java
    │       │   └── TicketSorterController.java
    │       ├── usermanagement/
    │       │   ├── CreatedialogController.java
    │       │   ├── DeletedialogController.java
    │       │   ├── ErrordialogController.java
    │       │   ├── LoginController.java
    │       │   ├── ManagementController.java
    │       │   ├── NewUserDialogController.java
    │       │   └── RegisterController.java
    │       ├── util/
    │       │   └── UserSession.java
    │       ├── AdminMainController.java
    │       ├── MainController.java
    │       └── Main.java
    │
    ├── module-info.java
    │
    └── resources/
        ├── apassignment.fxml
        ├── dashboard/
        │   └── dashboard.fxml
        ├── ticketingsystem/
        │   ├── newTicketForm.fxml
        │   ├── Ticket.fxml
        │   ├── TicketDetail.fxml
        │   └── TicketSorter.fxml
        ├── usermanagement/
        │   ├── createdialog.fxml
        │   ├── deletedialog.fxml
        │   ├── errordialog.fxml
        │   ├── login.fxml
        │   ├── management.fxml
        │   ├── newuserdialog.fxml
        │   └── register.fxml
        ├── AdminMain.fxml
        └── Main.fxml

project root/
├── closedTickets.txt
├── response.txt
├── ticket.txt
├── users.txt
├── pom.xml
├── mvnw
├── mvnw.cmd
├── .gitignore
└── target (generated)

---

## Requirements

- Java JDK 17+ (Tested with OpenJDK 24)
- JavaFX SDK
- IntelliJ IDEA or any Java IDE with JavaFX support

---

## How to Run

1. Ensure Java and JavaFX are properly installed on your system.
2. Download this file.
3. Open the project in IntelliJ IDEA.
4. Set the correct JDK (e.g., OpenJDK 24).
5. Run `Main.java`.

---

## Data Files Format

- `users.txt`:  
UserID , Username , Email , Password , Role
- `ticket.txt`:
TicketID | Subject | Status | Description | Priority | AssignedAgentUserID | SubmittedByUserID | dateSubmitted

- `response.txt`:
TicketID | ResponseByUserID | response | dateSubmitted

- `closedTickets.txt`:
closeID | TicketID | ClosedByUserID | dateClosed

---

## Authors

 Maureen Christopher Nyondo , 0380416 

 Naima Akter Nikita , 0377837 

 Maimuna Akter Orin , 0377869 

 Naima Rashid , 0373513 

 Ilsa Imaan bin Ilish Asmin , 0379294
