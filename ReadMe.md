# Company Management App

A full-stack application to manage companies, including functionalities like CRUD operations, pagination, sorting, and searching. The app allows you to add, edit, delete, and view company information.

## Features
- **Add a Company:** Users can add a new company to the system.
- **Edit Company:** Users can edit existing company details.
- **Delete Company:** Users can remove a company from the system.
- **Pagination:** The app supports pagination to navigate through large lists of companies.
- **Sorting:** Users can sort the table columns by clicking on the column headers (e.g., Name, Revenue, Employees).
- **Search:** Users can search for companies based on their name.

## Tech Stack
- **Frontend:**
  - React
  - React Bootstrap for UI components
  - Axios for making HTTP requests
- **Backend:**
  - Django (REST API)
  - Django REST Framework
- **Database:**
  - MySQL

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/yourrepository.git
cd yourrepository
```

### 2. Frontend Setup

- Navigate to the frontend directory:

```bash
cd frontend
```

- Install the necessary dependencies:

```bash
npm install
```

- Start the development server:

```bash
npm start
```

The app will be available at [http://localhost:3000](http://localhost:3000).

### 3. Backend Setup

- Navigate to the backend directory:

```bash
cd backend
```

- Install the necessary dependencies:

```bash
pip install -r requirements.txt
```

- Run the Django migrations:

```bash
python manage.py migrate
```

- Start the backend server:

```bash
python manage.py runserver
```

The API will be available at [http://127.0.0.1:8000](http://127.0.0.1:8000).

## How to Use

1. **Add a New Company:**
   - Use the "Add Company" form to input details such as name, revenue, profit, number of employees, and country.
   - The company will be saved to the database upon submission.

2. **View Companies:**
   - The list of companies will be displayed in a table format.
   - You can search for a company by name, sort by column (Name, Revenue, Profit, Employees, Country), and navigate through pages of data.

3. **Edit a Company:**
   - Click the "Edit" button next to a company to edit its details. The form will pre-fill with the company’s data for editing.

4. **Delete a Company:**
   - Click the "Delete" button next to a company to remove it from the database.

## API Endpoints

The backend API provides the following endpoints:

- **GET /api/companies/** - Get a list of companies with pagination.
- **POST /api/companies/** - Create a new company.
- **PUT /api/companies/{id}/** - Update an existing company.
- **DELETE /api/companies/{id}/** - Delete a company.

## Development Notes

- Make sure the backend is running and accessible when using the frontend.
- The frontend fetches data from the backend using Axios. If the backend changes its API endpoints, the frontend may need to be updated.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```

### **Explanation of Sections:**

1. **Overview:** Describes what the app does, which features are available, and which technologies are used.
2. **Installation:** Provides step-by-step instructions for setting up both the frontend and backend.
3. **How to Use:** Explains how users can interact with the application (adding, editing, deleting, and viewing companies).
4. **API Endpoints:** Lists the API endpoints used in the backend and their functionalities.
5. **Development Notes:** Mentions any important notes regarding the interaction between the frontend and backend.
6. **License:** If you use an open-source license, you can specify it here (this example uses MIT).

You can adjust or expand the content to fit your specific project.