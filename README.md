# ✅ ToDoApp (WPF)

A clean and minimal **.NET Core WPF** desktop application for managing daily tasks.  
Designed as a **personal productivity tool**, ToDoApp helps you quickly capture and track your todos in a lightweight, distraction-free interface.


## 🚀 Features

### 🧾 Core Functionality
- Add new to-do items instantly  
- Auto-clear input field after adding  
- Scrollable list for better task visibility  
- Simple **dark theme** UI  
- Lightweight and dependency-free

### 💾 Data Handling
- Data is **stored in memory** only while the app is running  
- Tasks reset when the application closes — ideal for quick, temporary lists

### 💡 UI Design
- Built entirely with **WPF XAML**  
- Responsive layout with grid system  
- Minimal styling for clarity and focus


## 🏗️ Project Structure

```
ToDoApp/
│
├── App.xaml/
│   └── App.xaml.cs
│
├── AssemblyInfo.cs
│
├── MainWindow.xaml/
   └── MainWindow.xaml.cs
```


## ⚙️ Technologies Used

| Category | Stack |
|-----------|--------|
| **Framework** | .NET Core (Microsoft.NETCore.App) |
| **UI Framework** | WPF (Microsoft.WindowsDesktop.App.WPF) |
| **Language** | C# |
| **IDE** | Visual Studio 2022+ |
| **Target OS** | Windows 10 / 11 |


## 🧠 Application Flow

1. Launch the app — it opens the main window.  
2. Type a task in the input field.  
3. Click **Create Todo** to add it to the list.  
4. The item appears below in a scrollable view.  
5. Close the app — all tasks are cleared (runtime only).


## 🪄 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/kanstantsin-malinouski/ToDoApp.git
cd ToDoApp
```

### 2. Build and Run
```bash
dotnet run
```


## 📜 License
This project is open-sourced for personal and educational use.
