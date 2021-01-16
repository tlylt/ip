This is a greenfield Java project. It's named HAHA. Given below are instructions on how to use it.

## Setting up in Intellij

Prerequisites: JDK 11, update Intellij to the most recent version.

1. Open Intellij (if you are not in the welcome screen, click `File` > `Close Project` to close the existing project dialog first)
1. Set up the correct JDK version, as follows:
   1. Click `Configure` > `Structure for New Projects` and then `Project Settings` > `Project` > `Project SDK`
   1. If JDK 11 is listed in the drop down, select it. If it is not, click `New...` and select the directory where you installed JDK 11
   1. Click `OK`
1. Import the project into Intellij as follows:
   1. Click `Open or Import`.
   1. Select the project directory, and click `OK`
   1. If there are any further prompts, accept the defaults.
1. After the importing is complete, locate the `src/main/java/Haha.java` file, right-click it, and choose `Run Haha.main()`. If the setup is correct, you should see something like the below:
```
Hello from
 _    _          _    _
| |  | |   /\   | |  | |   /\
| |__| |  /  \  | |__| |  /  \
|  __  | / /\ \ |  __  | / /\ \
| |  | |/ ____ \| |  | |/ ____ \
|_|  |_/_/    \_\_|  |_/_/    \_\
____________________________________________________________
Dude, I'm HAHA
What can I do for you?
(Oh when you are done, say bye)
____________________________________________________________
```
