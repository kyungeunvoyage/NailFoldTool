# 💅 Nail & Finger Stimulus Point Tool

A lightweight web-based tool that calculates and visualizes precise stimulus points on a nail and finger using canvas-based guidelines.

## ✨ Features
* **Local Image Upload**: Processes images securely within the browser without any server transmission.
* **Built-in Ruler**: Allows precise pixel-level coordinate tracking on the canvas.
* **Intuitive Click Interface**: Users can manually set U-Curves, vertical/horizontal guides, DIPJ, and outlines with simple mouse clicks.
* **Automated Stimulus Generation**: Automatically calculates six distinct stimulus points (a, b, c, d, e, f) based on the user-defined guidelines.
* **Zero Dependencies**: Built entirely with HTML5, CSS3, and Vanilla JavaScript.

---

## 📖 How to Use the Tool (Step-by-Step)

### Step 1: Load Your Image
1. Click the **Choose File** (Upload) button at the top left of the control panel.
2. Select and upload the target image of a nail/finger.

### Step 2: Set Guidelines
Click the respective mode buttons and then click directly on the canvas to set your reference points:
1. **`0. U-Curve (Click V1-V5)`**: Click **5 times** along the bottom curve of the nail from left to right.
2. **`1. Vertical Guide`**: Click **2 times** to mark the absolute top and absolute bottom of the nail.
3. **`2. Horizontal Guide`**: Click **2 times** to mark the absolute left and absolute right edges of the nail.
4. **`3. DIPJ Setting`**: Click **1 time** at the Distal Interphalangeal Joint (the first finger joint).
5. **`4. Finger Outline`**: Click **2 times** to mark the left and right outer boundaries of the finger.

### Step 3: Expand & Generate
1. **`7. Expand U-Curve`**: Adjusts and expands the initial U-Curve across the full width of the finger outline.
2. **`Generate Stimulus Points`**: Calculates and renders 6 specific yellow stimulus points (a, b, c, d, e, f).
3. **`Final Stimuli`**: Hides construction lines and displays only the original image, the expanded U-Curve, and the final stimulus points.

---

## 🚀 How to Upload & Deploy to GitHub (Step-by-Step)

If you are setting this up for the first time, follow these steps to upload your code to GitHub and host it live for free.

### Step 1: Create a Repository on GitHub
1. Log in to your [GitHub](https://github.com/) account.
2. Click the **"+"** icon in the top right corner and select **New repository**.
3. Enter a **Repository name** (e.g., `nail-stimulus-tool`).
4. Choose **Public** (recommended for free hosting) or **Private**.
5. Click **Create repository** *(Do NOT check "Add a README file" yet, since you are uploading this one).*

### Step 2: Prepare Your Local Files
Create a new folder on your computer and place the following two files inside:
1. `index.html` (The code for the tool)
2. `README.md` (This markdown file)

### Step 3: Upload Your Files
You have two options to upload:

**Option A: Drag & Drop (Easiest)**
1. On your new empty GitHub repository page, click the **"uploading an existing file"** link.
2. Drag and drop your `index.html` and `README.md` files into the box.
3. Click **Commit changes**.

**Option B: Using Git Command Line (Terminal)**
Open your terminal, navigate to your folder, and run:
```bash
git init
git add .
git commit -m "Initial commit: Add Nail Tool and README"
git branch -M main
git remote add origin [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
git push -u origin main
