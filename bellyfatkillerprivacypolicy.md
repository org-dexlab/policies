## Belly Fat Burn for Women: Privacy policy

Welcome to the Belly Fat killer Women app for Android!

This is an o Android app developed by Dexlab. The the app is also available on Google Play.


We hereby state, to the best of our knowledge and belief, that We have not programmed this app to collect any personally identifiable information. All data (app preferences (like theme, etc.) and alarms) created by the you (the user) is stored on your device only, and can be simply erased by clearing the app's data or uninstalling it.

### Explanation of permissions requested in the app

The list of permissions required by the app can be found in the `AndroidManifest.xml` file:


<br/>

| Permission | Why it is required |
| :---: | --- |
| `android.permission.SCHEDULE_EXACT_ALARM` | This is required to schedule an exact alarm, and was introduced in Android 12. You, as the user, or the system, can revoke this permission at any time from Settings. Revoking this permission will, however, kill the app immediately if it was alive, and cancel all alarms set by the app. |
| `android.permission.RECEIVE_BOOT_COMPLETED` | When your device restarts, all alarms set in the system are lost. This permission enables the app to receive a message from the system once the system has rebooted and you have unlocked your device the first time. When this message is received, the app creates a service to set all the active alarms in the system.|
| `android.permission.POST_NOTIFICATIONS`| On Android 13 Tiramisu ,you would need this permission to be able to enable or disable notifications 
| `com.google.android.gms.permission.AD_ID`| This permission is required by Google  if the app is showing the advertisement to the user.
 <hr style="border:1px solid gray">

If you find any security vulnerability that has been inadvertently caused by me, or have any question regarding how the app protectes your privacy, please send me an email or post a discussion on GitHub, and I will surely try to fix it/help you.

Yours sincerely,  
Dexlab    
dexlab.development@gmail.com
