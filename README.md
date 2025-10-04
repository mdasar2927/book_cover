
# Ex.06 Book Front Cover Page Design
# Date: 04-10-2025
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:

```
azarbook.html



<head>
  <title>Book Cover</title>
</head>
<body style="margin: 0; padding: 0; display: flex; justify-content: center; align-items: center; height: 100vh; background: #fff;">

<div style="width: 350px; height: 500px; background: linear-gradient(135deg, #00bcf2, #00b294); color: white; padding: 20px; position: relative; border: 5px solid #fff;">

    <p style="font-size: 14px; font-weight: bold; color: yellow;">SEC Insights</p>
    <hr>
    <h1 style="font-size: 30px; color: #000; font-weight: bold; text-align: center; line-height: 1.4;">MY LIFE JOURNERY<br>IN SEC</h1>
    <hr>
    <p style="font-size: 20px; text-align: center;">My life in saveetha engineering college</p>
    
    <p style="font-size: 14px; text-align: center;">Top seller of 2025</p>

<div style="display: flex; align-items: center;">
        
        <div style="position:absolute;bottom:100px;right:30px;width: 80px; height: 80px;border:5px solid grey;border-radius:25%;overflow:hidden;">
        <img src="kalam.jpg" alt="kalam.jpg" style="width: 100%; height: 100%;"></div>
            
    
        <div><p style="position:absolute;bottom:80px;right:56px;font-size: 14px; margin: 0;text-shadow:-1px -1px 0 #000,1px -1px 0 #000,-1px 1px 0 #000,1px 1px 0 #000;">Kalam</p>
        <p style="position:absolute;bottom:65px;right:56px;font-size: 14px; margin: 0;text-shadow:-1px -1px 0 #000,1px -1px 0 #000,-1px 1px 0 #000,1px 1px 0 #000;">2025-2029</p></div>
    
</div>

    <div style="position: absolute; bottom: 20px; left: 20px; font-size: 14px; font-weight: bold;">
         <img src="sign.png" alt="signature" 
       style="width:100px; height:auto; margin-bottom:-12px;">
      <p style="margin: 0; color: red;">SPECIAL EDITION</p></div>
    

</div>

</body>
</html>

views.py

from django.shortcuts import render
def book(request):
    return render(request,'azarbook.html')

urls.py

from django.contrib import admin
from django.urls import path
from bookcover import views
urlpatterns = [
    path('admin/', admin.site.urls),
    path('',views.bookcover),
]

```
# OUTPUT:

<img width="1289" height="940" alt="Screenshot 2025-10-03 173513" src="https://github.com/user-attachments/assets/a9ada107-b0e4-4e12-b419-dfef16962eb7" />

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
