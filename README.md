# Single-Page Application Routing
***Multiple Pages In Single-Page Apps***

- What & Why?
- Using **React Router**
- Data Fetching & Submission

**[What is a Routing?](https://www.canva.com/design/DAGUZeFzIEk/JNvvhxEUAVmKU876CcQ92Q/view?utm_content=DAGUZeFzIEk&utm_campaign=designshare&utm_medium=link&utm_source=editor)**

**[Multi-Page Routing](https://www.canva.com/design/DAGUZeSCu44/8pe2iINdFSjCoEkvyqFE8g/view?utm_content=DAGUZeSCu44&utm_campaign=designshare&utm_medium=link&utm_source=editor)**

**Building SPAs**

- When building complex user interfaces, we typically build ***Single Page Applications*** (SPAs)
- ***Only one initial HTML request & response***
- ***Page (URL) changes are then handled by client-side React code***
- Visible content is changed without fetching a new HTML file

**[React Router](https://reactrouter.com/en/main)**

**How To Use**

This project actually contains two projects:
- A React.js application (i.e., the frontend SPA)
- A dummy backend API to which the React app can "talk" (to send + fetch data)

You must run "npm install" in both project folders.

Thereafter, you can start the dummy backend API server via "npm start" (inside the "backend" folder).
The React app dev server is then also started via "npm start" (though inside the "frontend" folder).

You MUST have both servers (backend + frontend) up and running for the projects to work.

The dummy backend API does not use any external database - instead the dummy data is saved to an "events.json" file inside the project folder.

**Upgrading from React Router v5**

React Router v5 is also still used in many projects. In case you want to learn how to update from v5 to v6, the following two (free) videos should be very helpful:

- Upgrading from v5 to v6: https://www.youtube.com/watch?v=zEQiNFAwDGo
- Upgrading from v6 to v6.4 (introduced key data fetching features): https://www.youtube.com/watch?v=L2kzUg6IzxM
