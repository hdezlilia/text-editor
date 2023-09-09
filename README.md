# text-editor

## Description
This text editor web application allows users to create, edit, and save text content seamlessly. It includes features like a client-server folder structure, next-gen JavaScript support, IndexedDB storage for content, service worker integration, and Heroku deployment with proper build scripts.

## Table of Contents
- Usage
- Acceptance Criteria
- Technologies Used

## Usage
To use the Text Editor Web Application, follow these steps:

Clone the repository to your local machine.

Open the application in your preferred text editor.

Navigate to the root directory and run the command npm run start in your terminal. This will start up the backend server and serve the client.

Open the text editor application in your browser.

Create or edit text content in the editor.

The application uses IndexedDB for immediate database storage. Content is saved automatically when you click off the DOM window.

If you close the text editor and reopen it, your content will be retrieved from IndexedDB.

Click the "Install" button to download the web application as an icon on your desktop for easy access.

The web application is designed with service worker integration using Workbox, ensuring a reliable offline experience.

When deploying to Heroku, make use of the provided build scripts tailored for a webpack application.

## Acceptance Criteria
The Text Editor Web Application fulfills the following acceptance criteria:

1. Project Structure
When I open the application in my code editor, I should see a well-organized client-server folder structure.

2. Server Startup
When I execute the command npm run start from the root directory, the application should successfully initiate the backend server and serve the client.

3. JavaScript Bundling
Upon running the text editor application from my terminal, I should observe that my JavaScript files have been efficiently bundled using webpack.

4. Build Outputs
Running my webpack plugins should generate essential files, including an HTML file, service worker, and a manifest file.

5. ES6 Compatibility
When I utilize modern ES6 JavaScript features in my application, I expect the text editor to function seamlessly in the browser without encountering errors.

6. Database Initialization
Upon opening the text editor, IndexedDB should immediately create a database storage to facilitate data persistence.

7. Auto-Saving Content
As I input and interact with content within the text editor, any changes should be automatically saved to IndexedDB when I click off the DOM window.

8. Persistent Content
Should I close the text editor and subsequently reopen it, the application should successfully retrieve and display my previous content from IndexedDB.

9. Downloadable Web Application
By clicking the "Install" button, I should be able to conveniently download the web application, creating a desktop icon for easy access.

10. Service Worker Integration
Upon loading the web application, it should register a service worker using Workbox to ensure an uninterrupted experience even in offline conditions.

11. Heroku Deployment
When I deploy the application to Heroku, I anticipate that it will include appropriate build scripts tailored for a webpack-based application.

## Technologies Used
JavaScript
Node.js
npm
Webpack
IndexedDB
Service Worker (Workbox)
Heroku
