# How to update the ssl certificate for our website

1. Click on the link in the email.
2. Log into A2Hosting with the credentials. https://www.a2hosting.com/
  - Then go to the CPanal.
  - Scroll down to security.
3. Click AutoInstall
  - Copy the token from the email and paste it into the section and verify.
4.  Info to enter:
  
```
Domain webspace: starweatherfirends.org
CSR or CRS: Use www 
Mail: Leave the box checked for mail

Company name: Friends of Starkweather Creek
Divison: FSC
City: Madison
State: Wisconsin
Country: United States
Email: admin@starkweatherfriends.org

```

5. Enter your contact info.
6. Submit it.
  - It will take a few minutes.

Once done. Hit the `test` button.
Webbrowser check:

- Chrome: 
  1. Next to the url.
  2. Click on the Lock icon, on the left side of the url bar.
  3. Click on **certificate**.
    - Make sure it says valid.
  4. Look for **validity period**.
    - Make sure the date now is one year later.
    - For example. If its 1.1.2020 the new cert should say expires on 1.1.2021
  5.  Make sure the Common Name (CN) is: starkweatherfriends.org or www.starkweatherfriends.org

- Firefox:
  1. Next to the url.
  2. Click on the Lock icon, on the left side of the url bar.
  3. Click on **certificate**.
    - Make sure it says valid.
  4. Look for **validity period**.
    - Make sure the date now is one year later.
    - For example. If its 1.1.2020 the new cert should say expires on 1.1.2021
  5.  Make sure the **Common Name (CN)** is: starkweatherfriends.org or www.starkweatherfriends.org

- Safari:
  1. Next to the url.
  2. Click on the Lock icon.
  3. Click on **certificate**.
    - Make sure it says valid.
  4. Look for **validity period**.
    - Make sure the date now is one year later.
    - For example. If its 1.1.2020 the new cert should say expires on 1.1.2021
  5.  Make sure the **Common Name (CN)** is: starkweatherfriends.org or www.starkweatherfriends.org

- Internet Expolorer:
  1. Next to the url.
  2. Click on the Lock icon, on the right side of the url bar.
  3. Make sure the **issued to** is: starkweatherfriends.org or www.starkweatherfriends.org
  4. Look for the **valid from**
    - Make sure the date now is one year later.
    - For example. If its 1.1.2020 the new cert should say expires on 1.1.2021
  5.  Make sure the **website** is for starkweatherfriends.org or www.starkweatherfriends.org

- Edge:
  1. Next to the url.
  2. Click on the Lock icon, on the left side of the url bar.
  3. Click on **view certificate**.
    - Make sure it says valid.
  4. Look for **validity period**, the from & to section.
    - Make sure the date now is one year later.
    - For example. If its 1.1.2020 the new cert should say expires on 1.1.2021
  5. Near the top it will say starkweatherfriends.org or www.starkweatherfriends.org and **Valid certificate**

