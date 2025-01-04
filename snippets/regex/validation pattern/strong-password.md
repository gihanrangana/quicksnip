---
Title: Strong Password
Description: Match password with at least 12 characters, one uppercased letter, one number, and one special character.
Author: majvax
Tags: password
---


```regex
^(?=.*[A-Z])(?=.*[a-z])(?=.*\d)(?=.*[@$!%*?&])[A-Za-z\d@$!%*?&]{12,}$

-> Usage:
longpassword ✗
longpassw0rd ✗
longp@ssw0rd ✗
Longp@ssw0rd ✓
```