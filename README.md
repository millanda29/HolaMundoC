# 🌍 HolaMundoC - ASP.NET Core Web Application

Welcome to **HolaMundoC**, a basic web application built with **ASP.NET Core** using **Visual Studio 2022** and **.NET SDK 8**. This project introduces ASP.NET Core features and provides setup instructions for running it on any computer.

## 📋 Project Overview

HolaMundoC serves as a template for anyone interested in ASP.NET Core web applications, complete with setup instructions, project structure, and helpful resources.

---

## 🚀 Quick Start Guide

### 📌 Prerequisites

1. **Visual Studio 2022** – Download and install from [Visual Studio](https://visualstudio.microsoft.com/vs/).
   - During setup, select **"Web and Cloud Development"** to install ASP.NET Core tools.
2. **.NET SDK 8** – Ensure .NET 8 is installed. Check with:
   ```bash
   dotnet --version
   ```
   Download from [Microsoft .NET](https://dotnet.microsoft.com/download/dotnet/8.0) if needed.

---

## 🖥️ How to Duplicate This Project on Another Computer

### 1️⃣ Clone the Repository

To clone the repository to your computer, open a terminal and run:

```bash
git clone https://github.com/millanda29/HolaMundoC.git
```

### 2️⃣ Open the Project in Visual Studio 2022

1. Open **Visual Studio 2022**.
2. Select **"Open a project or solution"**.
3. Navigate to your cloned `HolaMundoC` folder and select the `.sln` file.

### 3️⃣ Restore Packages and Build the Project

Once the project is loaded in Visual Studio:

1. Visual Studio will automatically restore necessary packages.
2. Go to **Build > Build Solution** to ensure all dependencies are properly configured.

### 4️⃣ Run the Project

1. Choose the appropriate **debug profile** in the Visual Studio toolbar (e.g., "IIS Express" or the project name for `localhost`).
2. Click **Start** (or press `F5`) to launch the application.
3. Your default browser should open to `http://localhost:5000` (or another configured port).

---

## 🌐 Run the Project from Command Line (Optional)

To run the application directly from the terminal, navigate to the project directory and enter:

```bash
cd HolaMundoC
dotnet run
```

The app should be accessible at [http://localhost:5000](http://localhost:5000).

---

## 📁 Project Structure

- **`Pages/`** – User-facing views.
- **`wwwroot/`** – Static files (CSS, JavaScript, images).
- **`appsettings.json`** – Configuration settings.
- **`Program.cs`** – Main entry point.
- **`Startup.cs`** – Services and middleware configuration.

---

## ℹ️ Additional Resources

For more in-depth information, visit the [ASP.NET Core documentation](https://docs.microsoft.com/aspnet/core).

## 🔍 Important Notes

- Ensure **port 5000** is free or modify the port in `launchSettings.json`.
- Use **Git** to keep your project in sync across different systems.

---

Thanks for exploring **HolaMundoC**! 🎉 Happy Coding! 👨‍💻👩‍💻
