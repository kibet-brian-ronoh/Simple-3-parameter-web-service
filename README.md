# Simple-3-parameter-web-service
To run the web service from your computer, please folow these instructions: 
1. Download php 7.3 from here:https://windows.php.net/download/ 
2. Set up php environment variables by pressing win+r and type systempropertiesadvanced then click 'Environment Variables'.Look for 'path' in the system variables window,select it and click on edit.Now find the directory of the downloaded folder above. 
3. Save the php code on a desktop folder or any other folder 
4. Go to command window(press win+r and type cmd).Enter the following commands on the window: php -v (It should show the php version) 
5. Enter the next command: php -S localhost:8080 -t C:\Users\your\path\to\phpscriptfolder
6. Now the php development web server is running, go to your browser and input the following link:  http://localhost:8080/multiply_three_numbers.php?number1=4&amp;number2=12&amp;number3=3. It shows the result 144.
