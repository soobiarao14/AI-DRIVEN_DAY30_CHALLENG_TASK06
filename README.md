# Hi everyone

Here are some *important instructions for Task 6. These steps are required to create your **GitHub MCP Classic Token*, so please read and follow them carefully.


## 🔹 Step-by-Step Guide to Create a GitHub Personal Access Token (Classic)

### 1) Log in to GitHub
Sign in to your GitHub account from your browser.

### 2) Open Settings
Click your *profile photo* (top right) → select *Settings*.

### 3) Go to Developer Settings
On the left sidebar, scroll down and click *Developer settings*.

### 4) Open Personal Access Tokens
Click *Personal access tokens* → then choose *Tokens (classic)*.

### 5) Create a New Token
Click *Generate new token (classic)*.

### 6) Add a Token Name
Type any name you want, e.g. Gemini-MCP-Token.

### 7) Set Expiration
From the dropdown, select *No expiration*.

### 8) Select Repository Access
Make sure *All repositories* is selected for smooth MCP repo access.

### 9) Choose Permissions / Scopes
Tick the checkbox *repo* (recommended).  
- *If you do NOT tick repo*, then you must manually select these:  
  - *Contents: Read & Write*  
  - *Pull requests: Read & Write*  
  - *Issues: Read & Write*  
  - *Metadata: Read-only*  
  - *Actions: Read & Write* (optional)  
  - *Repository creation: Allow*  
  - *Repository deletion: Allow*

### 10) Generate & Copy Your Token
Scroll down, click *Generate token, and **copy it immediately*.  
You will not be able to view it again later.




*With this token, you can create, delete, and commit to repositories through the Gemini CLI using GitHub MCP.*
