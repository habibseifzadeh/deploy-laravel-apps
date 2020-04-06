# A simple script for deploying Laravel applications easily

## About

While there are numerous powerful continuous integration tools out there such as Jenkins, the following script automatizes some burdensome tasks of deploying Laravel applications. 

### Major benefits
1. As the Laravel programmers know, deploying Laravel applications, they must copy almost all the application's folders to the public folder of web server for security reasons. This makes changes to the index.php file of Laravel applications necessary so that it points to the correct paths. The provided script performs the task whenever the programmer deploys their applications.

2. Another deoployment concern of Laravel programmers is to clear previous cache settings in their development environment and set them in the server appropriately. The script does the task as well.

3. The script finally utilizes a *composer* package to remove any unnecessary package used by Laravel to improve the application performace as much as possible.

4. As I mentioned, the script is easy to use, and it can be executed with minimum software and hardware requirements.

# How to use
To use the script, you must set a couple of variables at the beginning of the script once. Then, whenever you would like to deploy your Laravel application, you should issue the command:

```bash
./update-app
```

Since the script has been written in *bash*, the user has to use terminals that support *bash* if they want to utilize it in Windows operating system. I myself use it in *Git bash* without any problem.

## Contact

Feel free to contact me should you have any question or feedbak via the address: habibseifzadeh at yahoo dot com. Your feedback would definitely be very valuable to imrove the script.
