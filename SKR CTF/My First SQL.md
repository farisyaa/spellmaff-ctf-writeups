# SKR CTF – My First SQL

* **Category:** Web Exploitation

![MFSQL](https://user-images.githubusercontent.com/65973879/201051188-6023984a-77a8-469b-99b4-7a5cbdbff2b0.png)

> This is about the basic SQL injection. Read this article if you got time https://portswigger.net/support/using-sql-injection-to-bypass-authentication

## Solution

1. Open the website and it redirects here.(without the flag tho)

![mfsql2](https://user-images.githubusercontent.com/65973879/201051592-27d68dc6-4a02-456f-b487-c0dde57dd4b4.png)

2. Then at the username i put any name and the pass, just put ' OR '1' = '1. It should show the page with the flag 

```
The flag is: SKR{Do_not_forget_to_escape_user_input_a73dce}
```
