# Time-and-space

Automatically detects and appends time and space complexity as comments
basically a Time & Space Complexity Annotator
A lightweight utility script and VS Code task integration that automatically analyzes the time and space complexity of Python functions and appends the result directly to the end of your source file.

##✨ ****Features****

✅ Automatically detects and appends time and space complexity as comments

🚀 Run via VS Code keyboard shortcut (Ctrl + Alt + C by default)

📂 Works on the currently open file in your editor

⚙️ Configured using tasks.json — no extensions required

🧠 Placeholder logic for complexity analysis

##📁 **How It Works**

Scans your Python file for logic patterns (e.g., loops, recursion)

Heuristically estimates the time and space complexities

Removes old annotations (if any) and adds new ones:

# Time Complexity: O(n)
# Space Complexity: O(n)
Triggered by a custom VS Code task or shortcut

###📦 **Project Structure**
###├── analyze_complexity.py   # Core script to process and annotate files
###└── .vscode
###    └── tasks.json          # VS Code task definition
