# Ingenious-Hackathon

## Demo Video

<iframe width="560" height="315" src="https://www.youtube.com/embed/DteJqgMTaok" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


<img src="https://user-images.githubusercontent.com/30389552/112749235-a7766d00-8fde-11eb-944f-47c0ab27af37.gif" width="300px" height="550px"/>       <img src="https://user-images.githubusercontent.com/30389552/112749235-a7766d00-8fde-11eb-944f-47c0ab27af37.gif" width="300px" height="550px"/>    <img src="https://user-images.githubusercontent.com/30389552/112749235-a7766d00-8fde-11eb-944f-47c0ab27af37.gif" width="300px" height="550px"/>

## Inspiration:

Owing to the current(covid) situation it is essential to have a system, which has minimum contact, for attendance. Biometric attendance possesses the risk of spreading bacteria among its users. So in the pursuit of a solution, we came up with an idea of taking attendance with the help of a camera sensor. The current systems were capable of processing only one user's request at a time, which was very inefficient. Hence the inspiration came from the pursuit of a solution for no contact attendance system.

## Accomplishments that we're proud of


Working Android App for Registering data of users like name, email, image of users with email authentication to Server [ to Django API ] which will store in the database, the App also shows the attendance logs of the Users and Statistics.

Working Android App for Monitoring the doors of the buildings/offices/rooms/colleges/lecture halls. It will capture the image of users and send it to the server for validation [ to Django API ] only when the face is visible inside the camera frame [ Thanks to Google vision API ], The Django API will compare the image with registered faces and generate the Attendance log in Firebase. The API returns a JSON response.


## What's next for 

We don’t have any IOT device with us that’s why we had created an Android App for monitoring. In Future what we can do is, We can use an IOT device like Raspberry pi for Monitoring which will call the Django API. We can also have multiple devices for Monitoring at different gates/doors.

Advance Leave Ticket - Whenever any user is going to take a leave then he/she can put a ticket in advance the duration of leave along with the reason.

Push Notification - Whenever any user is expected to be at any organization and he/she is absent then a notification mechanism will alert the user of the event.



