---
layout: post
title:  "Using Virtual Environments in Python"
date:   2024-09-02 00:03:33 +0300
categories: python
---
## Using Virtual Environments in Python

Virtual environments are crucial for managing dependencies in Python projects. They isolate your project’s dependencies, ensuring compatibility and preventing conflicts.

### Steps to Create a Virtual Environment:

1. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   ```
```bash
2. **Activate the Virtual Environment**:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS and Linux:
     ```bash
     source venv/bin/activate
     ```

3. **Install Project Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```