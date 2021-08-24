- 👋 Hi, I’m @smilekhan660
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
smilekhan660/smilekhan660 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
java.lang.RuntimeException: Unable to start activity ComponentInfo{com.amaze.filemanager/com.amaze.filemanager.ui.activities.DatabaseViewerActivity}: java.lang.NullPointerException
	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:3555)
	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:3699)
	at android.app.servertransaction.LaunchActivityItem.execute(LaunchActivityItem.java:83)
	at android.app.servertransaction.TransactionExecutor.executeCallbacks(TransactionExecutor.java:135)
	at android.app.servertransaction.TransactionExecutor.execute(TransactionExecutor.java:95)
	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:2267)
	at android.os.Handler.dispatchMessage(Handler.java:107)
	at android.os.Looper.loop(Looper.java:230)
	at android.app.ActivityThread.main(ActivityThread.java:7880)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:526)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1034)
Caused by: java.lang.NullPointerException
	at java.io.File.<init>(File.java:301)
	at com.amaze.filemanager.ui.activities.DatabaseViewerActivity.onCreate(DatabaseViewerActivity.java:71)
	at android.app.Activity.performCreate(Activity.java:7896)
	at android.app.Activity.performCreate(Activity.java:7885)
	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1353)
	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:3530)
	... 11 more
-------------------------------------
