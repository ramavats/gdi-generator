# GDI-Generator
Google Drive Index Generator for Cloudflare workers.

![[image.png]]

## Step 1:
Go to this URL : https://generate.cloudflare-us.workers.dev/

## Step 2:
Authorize your google account and get the authorization code. (Look for a string after ?code=**4/xxxxxxxx_xxxx_xxxxxxxxxxxxx**&scope)

## Step 3:
Paste that authentication code into the first field and Click on **Generate Code** button

## Step 4:
Copy the generated code and paste that in Cloudflare worker.js file.


> Note: 

This worker file is not created by me, I have just modified this file a little bit, so its working for now. 

Original worker is by **Praveen Bhadoo* : https://gitlab.com/GoogleDriveIndex/Google-Drive-Index 
