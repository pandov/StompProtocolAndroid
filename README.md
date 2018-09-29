# StompProtocolAndroid fix

STOMP client for Android
WebSocket client for Android

I did this because the original resource did not work for me

Source: https://github.com/NaikSoftware/StompProtocolAndroid

# To get a Git project into your build:

Step 1. Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}

Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.pandov:StompProtocolAndroid:-SNAPSHOT'
	}
