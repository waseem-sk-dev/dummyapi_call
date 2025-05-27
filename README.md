---
## Angular Dummy API Call

This project demonstrates a simple Angular application that performs a **dummy API call** using Angular’s `HttpClientModule`. It's designed as a beginner-friendly example to show how to fetch data from an external REST API and display it in a component.

##  Features

- Angular 16+ setup
- Uses `HttpClient` for API integration
- Dummy GET request to [JSONPlaceholder](https://jsonplaceholder.typicode.com/posts)
- Data display using `*ngFor`
- Clean folder structure for easy learning

---

##  Project Structure
```
src/
├── app/
│ ├── app.component.ts
│ ├── app.component.html
│ ├── app.service.ts
│ └── app.module.ts
├── assets/
└── index.html
```
---

##  Getting Started

### Prerequisites
- Node.js and npm installed
- Angular CLI installed (`npm install -g @angular/cli`)
---
### Installation
```bash
git clone https://github.com/waseem-sk-dev/dummyapi_call.git
cd dummyapi_call
npm install
```
---
## Run the Application
```
ng serve
```
---
Navigate to http://localhost:4200/ to view the app.
---
## API Used
URL: https://jsonplaceholder.typicode.com/posts

Type: GET

Description: Returns a list of dummy blog posts
---
## Screenshots
# For Retriving Single Data
![image](https://github.com/user-attachments/assets/c2c68789-1b2e-4a21-b1fb-6dd00057fc4d)
# For Retriving Multiple Data
![image](https://github.com/user-attachments/assets/d9084e49-7023-42d0-8c0c-c3bf24c3a678)
---
## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.

## Contact
Created by Waseem SK – feel free to reach out!
Let me know if you’d like to include [API error handling](f), [pagination](f), or [UI styling tips](f) to enhance your project.
