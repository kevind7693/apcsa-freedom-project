# Entry 4
##### 4/09/2021

We are still currently working on learning our tools part of the engineering design process, but being more active in putting them to use as of the moment. Since we all have a mvp plan in motion that we want to follow through in order to finish this project. Most work is being done on the [ide.cs50 site](https://ide.cs50.io/) and the [firebase-console site](https://console.firebase.google.com/u/0/project/proje-76d28/database/proje-76d28-default-rtdb/data).

During the break and the following week, I was working on how to connect the actual firebase tool onto my web application. I found that the instructions on the firebase [site](https://firebase.google.com/docs/database/web/start) was a little bit unclear on how to link your firebase project with your web application. All it says is paste these lines of code with no other further instructions. So naturally I decide to look around google and youtube for firebase tutorial videos. Most of the videos were made using older versions of firebase but the concept remained the same. Here is one of the [video](https://www.youtube.com/watch?v=S8D9Cxb2lLA&t=196s) I watched that give me some insight on what to do.

For testing purposes, I made a simple web app with 5 different text-boxes and one button. The 5 textboxes are used to hold the data that is being typed in while the button will initialize the app to store the responses typed. Most of the firebase code was gotten from the firebase site, like the one which allows firebase to work on my web app. While the other one connects my wed app with the firebase real-time database.

This line of code is what allows our app to connect to our firebase project's database.
```  <script src="https://www.gstatic.com/firebasejs/8.3.2/firebase-database.js"></script>
```

The JavaScript client SDK code which allows us to use firebase.
```<script src="https://www.gstatic.com/firebasejs/8.3.3/firebase-app.js"></script>
```

Examples of real-life data being transfered from web app to my firebase project database:
![app](/img/app.PNG "app")
![database](/img/database.JPG "database")

Next step being getting my MVP ready and after that is finished I can focus on how in dept components that I want on the app but not what I need.


[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)