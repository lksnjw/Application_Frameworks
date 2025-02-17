

---

# **🚀 Step 1: Create a New Folder**
First, create a folder where you will store your project.

### **Windows (Command Prompt or Git Bash)**
Open **Command Prompt** or **Git Bash**, and run:

```sh
mkdir MyProject
cd MyProject
```

### **Mac/Linux (Terminal)**
```sh
mkdir MyProject
cd MyProject
```

Now, you are inside your project folder.

---

# **🚀 Step 2: Initialize a Git Repository**
Inside the folder, initialize Git:

```sh
git init
```

This will create a `.git` folder, making this directory a Git repository.

To check if Git initialized successfully, run:

```sh
git status
```

It should show something like:

```
On branch master
No commits yet
nothing to commit (create/copy files and use "git add" to track)
```

---

# **🚀 Step 3: Set Up Your Git Username and Email**
Before making any commits, set up your **Git username and email**.

```sh
git config --global user.name "Your Name"
git config --global user.email "your_email@example.com"
```

To verify:

```sh
git config --global user.name
git config --global user.email
```

You should see your name and email as output.

---

# **🚀 Step 4: Create a New File**
Let’s create a new file for testing.

```sh
echo "Hello Git!" > README.md
```

Check if the file exists:

```sh
ls
```

(Use `dir` instead of `ls` in Windows Command Prompt.)

---

# **🚀 Step 5: Check Git Status**
Run:

```sh
git status
```

You will see something like:

```
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
```

---

# **🚀 Step 6: Add Files to Staging**
To add the file to **staging**, use:

```sh
git add README.md
```

If you want to add **all** files, use:

```sh
git add .
```

Check the status again:

```sh
git status
```

Now you will see:

```
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   README.md
```

---

# **🚀 Step 7: Commit Your Changes**
Once the file is added, commit the changes:

```sh
git commit -m "Initial commit"
```

This saves your changes to Git history.

---

# **🚀 Step 8: Create a New Repository on GitHub**
1. Go to [GitHub](https://github.com/).
2. Click the **+ (New Repository)** button in the top-right.
3. Give your repository a name (e.g., `MyProject`).
4. Keep it **Public** or **Private**.
5. Click **Create Repository**.
6. Copy the **HTTPS** link of your new repository.

---

# **🚀 Step 9: Connect Local Repo to GitHub**
Now, **link your local repository** to GitHub:

```sh
git remote add origin https://github.com/yourusername/MyProject.git
```

To verify:

```sh
git remote -v
```

You should see:

```
origin  https://github.com/yourusername/MyProject.git (fetch)
origin  https://github.com/yourusername/MyProject.git (push)
```

---

# **🚀 Step 10: Push Your Code to GitHub**
Now, push your local commits to GitHub:

```sh
git push -u origin master
```

If prompted, enter your GitHub **username and password** (or use a **personal access token** if required).

After this, visit your **GitHub repository**, and you should see your `README.md` file uploaded.

---

# **🚀 Other Useful Git Commands**
### **1️⃣ Check Git Status**
```sh
git status
```

### **2️⃣ Add More Files**
```sh
git add .
```

### **3️⃣ Commit Changes**
```sh
git commit -m "Updated files"
```

### **4️⃣ Pull Latest Changes from GitHub**
```sh
git pull origin master
```

### **5️⃣ Push More Changes**
```sh
git push origin master
```

---

