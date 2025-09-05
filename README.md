# Mini-DBMS

A miniature relational database management system implemented in **C++**, designed for learning and experimentation with core DBMS features.

## Table of Contents

1. [Overview](#overview)  
2. [Features](#features)  
3. [Getting Started](#getting-started)  
   - [Prerequisites](#prerequisites)  
   - [Build & Run](#build--run)  
   - [Running Tests](#running-tests)  
---

## Overview

This project implements a simplified relational DBMS from scratch in **C++**.  
It supports SQL-like commands for creating, querying, updating, and deleting tables. Designed as a learning project, it demonstrates fundamental concepts in database internals, query parsing, and command-line interaction.

---

## Features

- **SQL-style CRUD operations**: create table, insert, select, delete, and update.  
- **Disk persistence**: `load` and `store` commands for saving/loading tables.  
- **Robust error handling**: handles invalid commands gracefully without crashing.  
- **Spelling suggestions**: uses longest common substring logic to offer hints for mistyped commands.  
- **Unit testing**: suite of automated tests to validate core functionality.

---

## Getting Started

### Prerequisites

- **C++17 or later**  
- **CMake** (for building)  
- **g++ / clang++** compiler  

---

### Build & Run

```bash
# Clone the repository
git clone https://github.com/your-username/mini-dbms.git
cd mini-dbms

# Build
mkdir build
cd build
cmake -G "MinGW Makefiles" ..
mingw32-make
cd ..

# Run the DBMS
./mini_dbms
```
### Running Tests

``` bash
cd build/tests
./mini_dbms_test
```

