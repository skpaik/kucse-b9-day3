## **Final Tasks for Student (B9) Test Project**  

### **Backend (FastAPI - Machine Learning with RandomForest)**  

#### **Setup Instructions**  
1. Create a new project folder.  
2. Create a Python virtual environment inside the folder.  
3. Activate the virtual environment.  
4. Install **FastAPI** and required dependencies.  
5. Copy the tutorial code and run the project by following tutorials.  

#### **Endpoints to Implement**  
1. **`/learn` Endpoint** (POST Method)  
   - Accepts a `.csv` file uploaded from the frontend.  
   - Uses the **RandomForest** algorithm from **scikit-learn** to train a machine-learning model using the CSV data.  
   - Stores the trained model for later use.  

2. **`/ask` Endpoint** (GET Method)  
   - Accepts a **question** as a query parameter (`q`).  
   - Uses the previously trained model to generate a prediction based on the learned data from the `.csv` file.  
   - Returns the result as a JSON response.  

---

### **Frontend (Next.js - Upload & Query System)**  

#### **Setup Instructions**  
1. Create a new Next.js project.  
2. Install required libraries for handling file uploads and API requests.  
3. Build the UI to interact with the backend.  

#### **Features to Implement**  
1. **Learn Page**  
   - A simple form with a file input to upload a `.csv` file.  
   - Calls the `/learn` endpoint in the backend to train the model.  
   - Displays a success message once training is complete.  

2. **Ask Page**  
   - A text input where users can enter a question.  
   - Calls the `/ask` endpoint to get a response from the trained model.  
   - Displays the predicted result on the screen.  

---

### **Deliverables**  
- Working **FastAPI** backend with machine-learning capabilities.  
- Functional **Next.js** frontend for file upload and question-answering.  
- Clear documentation for setup and usage.
- Push both frontend and backend code to a github repository, then share the repository link with me.
- Do not push `venv` or `node_modules` folder in github or ClassRoom.

This setup will allow students to build a simple **machine-learning-based Q&A system** using **FastAPI** and **Next.js** while learning about backend and frontend integration. 🚀

---

### **Github Learning**  
- Learn how to create github account
- Learn how to create github respositiry
- Learn how to push in github repository from your local computer.
