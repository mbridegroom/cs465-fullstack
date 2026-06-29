# cs465-fullstack
CS-465 Full Stack Development with MEAN

 ** Architecture**
The project uses both Express HTML and a Single Page Application (SPA) built with Angular. Express HTML generates full pages from the server, while the SPA loads once and updates content dynamically without page reloads. JavaScript is used in both for logic and interaction, but the SPA is more organized through components and services. The backend uses MongoDB because it is flexible, works well with JavaScript, and stores data in a JSON-like format.

**  Functionality**
JSON is a data format used to transfer information, while JavaScript is the language used to build application logic. JSON connects the frontend and backend by allowing data to be sent and received through API requests. Code was refactored by moving repeated logic into services and reusable components like trip cards, which improved consistency and reduced duplication.

**  Testing**
HTTP methods like GET, POST, and PUT are used to interact with backend endpoints. Testing involves checking these endpoints to ensure correct data flow between the frontend, backend, and database. Security, such as JWT authentication, requires testing protected routes to make sure only authorized users can access certain data.

**  Reflection**
This course helped me understand how full stack applications work together from frontend to backend. I gained experience with Angular, Express, and MongoDB, as well as building and testing APIs. These skills improved my ability to develop and troubleshoot web applications.
