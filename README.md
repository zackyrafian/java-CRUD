# Java Desktop CRUD Application

A desktop-based CRUD (Create, Read, Update, Delete) application built with Java Swing and MySQL. This project demonstrates a simple yet functional biodata management system with a clean user interface.

![Java Version](https://img.shields.io/badge/Java-8+-orange.svg)
![MySQL](https://img.shields.io/badge/MySQL-latest-blue.svg)


##  Installation & Setup

1. Clone the repository
```bash
git clone https://github.com/zackyrafian/java-CRUD.git
```

2. Setup MySQL Database
```sql
CREATE DATABASE pv_biodata;
USE pv_biodata;
```

3. Configure Database Connection
- Open `config/KoneksiDB.java`
- Update database credentials if needed:
```java
String url = "jdbc:mysql://localhost:3306/pv_biodata";
String user = "root";
String password = "";
```

4. Run the Application
- Locate and run `FormBiodata.java`

##  Usage

The application offers straightforward CRUD operations:

1. **Create:** Add new biodata entries
2. **Read:** View existing records in table format
3. **Update:** Modify existing records
4. **Delete:** Remove unwanted entries

## 



