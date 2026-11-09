# Mafia-Puzzles-The-Escape-Part-1
MyApp/
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── assets/
│   │       │   └── index.html      <-- Put your HTML file here
│   │       ├── java/com/example/myapp/
│   │       │   └── MainActivity.java
│   │       └── AndroidManifest.xml
│   ├── build.gradle
   └── build.gradle (project level)
   <manifest xmlns:android="http://schemas.android.com/apk/res/android"
    package="com.example.myapp">

    <uses-permission android:name="android.permission.INTERNET" />

    <application
        android:allowBackup="true"
        android:icon="@mipmap/ic_launcher"
        android:label="MyHTMLApp"
        android:roundIcon="@mipmap/ic_launcher_round"
        android:supportsRtl="true"
        android:theme="@style/Theme.AppCompat.Light.NoActionBar">
        
        <activity
            android:name=".MainActivity"
            android:exported="true">
            <intent-filter>
                <action android:name="intent.action.MAIN" />
                <category android:name="intent.category.LAUNCHER" />
            </intent-filter>
        </activity>
    </application>
</manifest><manifest xmlns:android="http://schemas.android.com/apk/res/android"
    package="com.example.myapp">

    <uses-permission android:name="android.permission.INTERNET" />

    <application
        android:allowBackup="true"
        android:icon="@mipmap/ic_launcher"
        android:label="MyHTMLApp"
        android:roundIcon="@mipmap/ic_launcher_round"
        android:supportsRtl="true"
        android:theme="@style/Theme.AppCompat.Light.NoActionBar">
        
        <activity
            android:name=".MainActivity"
            android:exported="true">
            <intent-filter>
                <action android:name="intent.action.MAIN" />
                <category android:name="intent.category.LAUNCHER" />
            </intent-filter>
        </activity>
    </application>
</manifest>
