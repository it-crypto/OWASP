# Juice Shop

* Lets start with user account as we dont have any credentials lets try to create a user and check

  ![image](https://github.com/it-crypto/OWASP/assets/54020728/72aef395-97d4-41fe-a0aa-3c99b5f94f2a)

  ![image](https://github.com/it-crypto/OWASP/assets/54020728/caf4e710-0f5e-49c1-8fde-73c9c6605c7e)

  ![image](https://github.com/it-crypto/OWASP/assets/54020728/7f3c1090-9c04-458e-a8a8-7d3e94794f41)

* I have tried to check from login page where it is vulnerbale to SQLi
* So I tried using the most common string(single quote('))

  ![image](https://github.com/it-crypto/OWASP/assets/54020728/cff677ad-9ba9-474d-8b84-10c8b90d4c0c)

* In burpsuite when intercepting this request we can see that more detailed information how the sql query is being processed and how it resulting in an error.
  
  ![image](https://github.com/it-crypto/OWASP/assets/54020728/95e486f7-2bf9-45a9-8435-7026718893be)

* When using the sql injection payload in the username field, we are able to get access to admin account

  ![image](https://github.com/it-crypto/OWASP/assets/54020728/d5a45b28-6603-4964-992f-c0aa347ea8a6)

# Challenge - Empty User Registration

  ![image](https://github.com/it-crypto/OWASP/assets/54020728/6c843f0f-c112-4771-9492-9273549017cc)

  ![image](https://github.com/it-crypto/OWASP/assets/54020728/c7030ae8-cba0-41b8-b2ba-19f16a6bc66b)


  



