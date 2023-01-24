# face-recognition-based-attendance-system

Hello, I'm Armaan Sidhu, Member of the Team - "House of the Dragon" which created this Face Recognition based Attendance System for T-Hunt Hackathon which was conducted on 19th and 20th January 2023.

Steps to Implement the Program :

- Extract the Folder inside the Downloaded "Code.zip" to any Destination you like.
- Open the file "Home.html" inside templates folder in VS Code
- Open Terminal and Input "Flask run" inside it.
- The terminal will display a message indicating the IP Address on which the file is running. Open the address in a browser.
- Click "Add new user" for registering the user. A Face Scanning window will open which will take 100 images of the individual's face in some seconds.
- Press "Escape" key on the keyboard once 100 images are done. This will close the Face Scanning Window.
- Now the 100 Images will get stored in "static/faces". Click "Take Attendance" in order to save your attendance.
- The Model will automatically detect the user if his database was earlier registered via "Add new user".
- The User's attendance will be displayed on the Website as well as in that date's corresponding excel file in "Attendance" folder, file will be auto created the first time and next time onwards updated.
- Once the day is completed (ie, after 23:59) the attendance data on Website will automatically get erased in order to allow fresh day's atendance data to be displayed.
- All the attendance of following day will be saved in that day's corresponding Excel files automatically.
