# **📄 Google Docs API Integration Project**

This project demonstrates how to use the Google Docs API in Google Colab to:
- Create and format Google Docs
- Upload and convert Markdown files with proper styling
- Apply distinct styles for assignee mentions and footer information

---

## **🚀 Features**
- 🗂️ **Create Google Docs:** Automatically create new Google Docs files.
- 📝 **Markdown Support:** Upload and convert Markdown files with headings, bullet points, and checkboxes.
- 👥 **Mentions Styling:** Assignee mentions are styled in **bold and blue**.
- 📄 **Footer Styling:** Footer information is styled in *italic and gray*.

---

## **📦 Setup**

### **Step 1: Clone the Repository**
```bash
git clone https://github.com/sid-pandya/Meeting-Notes-to-Doc.git
```
### Step 2: Install Required Python Packages
`pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib`

* * *

### Step 3: Configure Google API in Colab

*   Open the notebook in **Google Colab**.
*   Run the following command to authenticate:
    
    `from google.colab import auth auth.authenticate_user()`
    
* * *

## 🛠️ How to Run

### 1\. Upload Your Markdown File

*   Run the notebook.
*   Use the upload prompt to select your `.md` file.

* * *

### 2\. Create and Format Google Doc

*   The notebook will:
    *   Create a new Google Doc.
    *   Append content with proper formatting.
    *   Style mentions and footers distinctly.

* * *

### 3\. Check Your Google Doc

*   Visit the generated **Google Doc link** to view the formatted content.
