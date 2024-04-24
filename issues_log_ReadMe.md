





```

37s
Build APK
20s



Show command

Upgrading build.gradle

Upgrading build.gradle
Running Gradle task 'assembleRelease'...                        
You are applying Flutter's app_plugin_loader Gradle plugin imperatively using the apply script method, which is deprecated and will be removed in a future release. Migrate to applying Gradle plugins with the declarative plugins block: https://flutter.dev/go/flutter-gradle-plugin-apply

Running Gradle task 'assembleRelease'...                        
You are applying Flutter's app_plugin_loader Gradle plugin imperatively using the apply script method, which is deprecated and will be removed in a future release. Migrate to applying Gradle plugins with the declarative plugins block: https://flutter.dev/go/flutter-gradle-plugin-apply


FAILURE: Build failed with an exception.

* Where:
Build file '/Users/builder/clone/android/app/build.gradle' line: 28

* What went wrong:
A problem occurred evaluating project ':app'.
> Failed to apply plugin [id 'kotlin-android']
   > The current Gradle version 5.6.4 is not compatible with the Kotlin Gradle plugin. Please use Gradle 6.1.1 or newer, or the previous version of the Kotlin plugin.

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output. Run with --scan to get full insights.

* Get more help at https://help.gradle.org

BUILD FAILED in 18s
Running Gradle task 'assembleRelease'...                           19.0s

┌─ Flutter Fix ────────────────────────────────────────────────────────────────────┐
│ [!] Your project needs to upgrade Gradle and the Android Gradle plugin.          │
│                                                                                  │
│ To fix this issue, replace the following content:                                │
│ /Users/builder/clone/android/build.gradle:                                       │
│     - classpath 'com.android.tools.build:gradle:<current-version>'               │
│     + classpath 'com.android.tools.build:gradle:7.3.0'                           │
│ /Users/builder/clone/android/gradle/wrapper/gradle-wrapper.properties:           │
│     - https://services.gradle.org/distributions/gradle-<current-version>-all.zip │
│     + https://services.gradle.org/distributions/gradle-7.6.3-all.zip             │
└──────────────────────────────────────────────────────────────────────────────────┘
Gradle task assembleRelease failed with exit code 1


Build failed :|
Step 4 script `Build APK` exited with status code 1

FAILURE: Build failed with an exception.

* Where:
Build file '/Users/builder/clone/android/app/build.gradle' line: 28

* What went wrong:
A problem occurred evaluating project ':app'.
> Failed to apply plugin [id 'kotlin-android']
   > The current Gradle version 5.6.4 is not compatible with the Kotlin Gradle plugin. Please use Gradle 6.1.1 or newer, or the previous version of the Kotlin plugin.

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output. Run with --scan to get full insights.

* Get more help at https://help.gradle.org

BUILD FAILED in 18s
Running Gradle task 'assembleRelease'...                           19.0s

┌─ Flutter Fix ────────────────────────────────────────────────────────────────────┐
│ [!] Your project needs to upgrade Gradle and the Android Gradle plugin.          │
│                                                                                  │
│ To fix this issue, replace the following content:                                │
│ /Users/builder/clone/android/build.gradle:                                       │
│     - classpath 'com.android.tools.build:gradle:<current-version>'               │
│     + classpath 'com.android.tools.build:gradle:7.3.0'                           │
│ /Users/builder/clone/android/gradle/wrapper/gradle-wrapper.properties:           │
│     - https://services.gradle.org/distributions/gradle-<current-version>-all.zip │
│     + https://services.gradle.org/distributions/gradle-7.6.3-all.zip             │
└──────────────────────────────────────────────────────────────────────────────────┘
Gradle task assembleRelease failed with exit code 1


Build failed :|
Step 4 script `Build APK` exited with status code 1

```