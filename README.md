Advanced UI Implementation: Notification Panel with Modal Pop-up
Project Overview
This project is an advanced UI implementation featuring a responsive notification panel with a modal pop-up, along with a collapsible sidebar and dynamic interactivity. The layout is designed to be fully responsive across various screen sizes, including functionalities like notification management, marking notifications as read/unread, and a dynamic counter for unread notifications.

Features
Header with Notification Icon:

Displays a notification bell icon with a dynamic counter showing the number of unread notifications.
The counter updates based on the notifications stored in local storage.
Notification Panel:

A side panel slides out when the notification icon is clicked, listing all notifications in descending order.
Unread notifications have a grey background.
Read notifications have a white background and include a "mark as unread" text.
The panel includes a close button to hide the panel.

Modal Pop-up:

Clicking on a notification opens a modal window displaying the full content of the notification.
Notifications are marked as read when opened, with corresponding color updates in the notification panel.
Notification Management:

Functionality to mark notifications as read/unread.

Sidebar:

A collapsible sidebar with menu items like Dashboard, Reports, Settings, and Logout.
 
Responsiveness:

The design automatically adapts to different screen sizes (desktop, tablet, mobile).
The sidebar can be manually toggled on larger screens.
Project Structure
All HTML, CSS, and JavaScript code is contained within a single index.html file for simplicity. The project uses embedded CSS within the <head> section and JavaScript within <script> tags at the bottom of the file.

Technologies Used
HTML5: For the structure of the webpage.
CSS3: For styling and layout.
JavaScript: For dynamic interactivity and DOM manipulation.
Bootstrap 4/5: For responsive grid structure and basic styling.
Font Awesome: For icons used in the sidebar and notifications.
Setup Instructions
Clone the Repository:

bash
Copy code git clone https://github.com/sethuvicky/growth99

cd growth99

Open the Project:

Open the index.html file in your preferred web browser.
Interacting with the UI:

Click on the notification bell icon to open the notification panel.
Click on any notification to view its full content in a modal pop-up.
Use the sidebar's toggle button to expand/collapse the sidebar.
On smaller screens, the sidebar automatically collapses into a hamburger menu.
Local Storage
The project uses local storage to simulate dynamic content loading and notification management. Notifications are initialized if they are not already set in the local storage.

Code Structure
Notification Management:

Notifications are stored and managed in local storage.
The notification panel dynamically updates based on the current state of notifications.
The notification counter reflects the number of unread notifications.
Sidebar Toggle:

The sidebar expands/collapses based on the screen size and user interactions.
Modal Pop-up:

A modal window displays the full content of a notification when clicked.
Comments
The code is well-commented to explain the logic and structure. Please refer to the comments in the index.html file for detailed explanations of each functionality.

Testing
The project has been tested across various devices to ensure responsiveness and cross-browser compatibility.
