# How to Use This Custom GPT for Resume & Cover Letter Assistance

This GPT is designed to **analyze resumes, generate cover letters, and assess job fit** based on uploaded documents. Follow the steps below to use it effectively.

---

## Step 1: Upload Your Files

Before issuing commands, upload the necessary files:

1. **Resume File** – Upload **one** resume document (referred to as **cv**).
2. **Job Description File** – Upload **one** job description document (referred to as **job**).
3. **(Optional) worldview.docx** – If provided, this document will:
   - Supply your **full address** for cover letters.
   - Provide **personal values or preferences** for job fit analysis.

Once the files are uploaded, you can begin using commands.

---

## Step 2: Commands & Their Usage

Use the following commands to interact with the system:

### 1. Get Resume Improvement Suggestions

**Command:**  
```
resume
```
- Analyzes your **cv** and **job** files.
- Provides **specific recommendations** to improve your resume for better alignment with the job description.

---

### 2. Generate a Cover Letter

**Command:**  
```
cover,Y
```
- Generates a **tailored cover letter** with a maximum of **Y** words.
- Uses **worldview.docx** for your **address** if available.
- The cover letter is formatted **compactly**, with **no extra spacing** between the address and paragraphs.

📌 *Example (100-word cover letter):*  
```
cover,100
```

---

### 3. Analyze Job Fit

**Command:**  
```
fit-C,Z
```
- Compares your **cv** and **job** against the **company website (Z)** to assess alignment.
- Uses **worldview.docx** (if available) for personal preferences.
- Focus areas (**C**) can be:
  - **C** → Culture Fit
  - **I** → Industry Relevance
  - **S** → Specific Skills Match
  - **A** → All of the Above

📌 *Example (Assess skills match using company website example.com):*  
```
fit-S,example.com
```

---

### 4. Download the Cover Letter

**Command:**  
```
download
```
- Saves the last generated **cover letter** as a **DOCX file**.
- The filename format is:  
  ```
  Cover_Letter_for_[job filename].docx
  ```
  (Example: `Cover_Letter_for_pd-123.docx`)

---

### 5. Reset Files

#### Clear Resume & Job Description (Keep worldview.docx)
**Command:**  
```
reset
```
- Removes only **cv** and **job** files.
- Keeps **worldview.docx** for future use.

#### Clear Everything (Including worldview.docx)
**Command:**  
```
reset all
```
- Removes **cv, job, and worldview.docx**.

---

### 6. Get Help

**Command:**  
```
help
```
- Lists available commands.
- To get details on a specific command, use:  
  ```
  help [command]
  ```
📌 *Example:*  
```
help cover
```

---

## Final Notes

- This system processes **one** resume and **one** job description at a time.
- Use `"reset"` before uploading new files.
- If no **worldview.docx** is uploaded, the cover letter will exclude an address section.

---

By following these steps, you can efficiently **refine your resume, create strong cover letters, and analyze job fit** using this GPT. 🚀
