# StudentGrade - Software Maintenance Assignment

## 📌 Overview
This project is part of the **Software Maintenance and Evolution** course, where I performed maintenance on an existing Java application. The tasks included **migrating the project from NetBeans (Ant) to Maven**, upgrading **JUnit from version 3.8.1 to JUnit 4**, and managing the project using **Git and GitHub**.

---

## 🛠 Tasks Performed
### **1️⃣ Migration from NetBeans (Ant) to Maven**
- The original project was built with **Ant** and had NetBeans-specific files (`nbproject/`, `build.xml`, `manifest.mf`).
- I **converted** it into a **Maven project**, making it more manageable and compatible with modern Java development.
- Unnecessary files were **removed** and `.gitignore` was updated to exclude NetBeans-related files.

### **2️⃣ Upgrading JUnit from 3.8.1 to 4**
- The project originally used **JUnit 3.8.1**, which required extending `TestCase` and didn’t support modern annotations.
- I **migrated the test class** to **JUnit 4**, replacing `TestCase` inheritance with the `@Test` annotation.
- Updated `pom.xml` to include **JUnit 4** as a dependency.

### **3️⃣ Setting Up Git & GitHub**
- Initialized the project with **Git** and created a repository on **GitHub**.
- Created a dedicated **branch `update-junit`** for modifications.
- Removed unnecessary files from tracking and added proper `.gitignore` rules.
- Merged `update-junit` into `main` while resolving conflicts.

