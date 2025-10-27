# Secret Actions (shortcut)
__Shortcut for iOS and macOS that contains 30+ hidden actions__
\
\
[Click here to install the latest signed version](https://github.com/paralevel/secret-actions.shortcut/releases)
\
\
\
__How to sign the shortcut from source__

macOS:
~~~
shortcuts sign -m anyone -i Secret\ Actions.unsigned.shortcut -o Secret\ Actions.shortcut
~~~

iOS: Use RoutineHub's signing service
\
\
\
__How hidden Shortcuts actions can be found__

1. Copy for example the hidden action in the following shortcut to the clipboard: https://www.reddit.com/r/ios/comments/1h8akxn/comment/m0sgf4d/

3. Convert the action in the clipboard to source with this shortcut: https://www.icloud.com/shortcuts/65d36be39c5a49cc8121e4ea652b606e

3. Open the source in a text editor

4. Replace `AutoBrightness` with e.g. `BoldText` in the value for `WFWorkflowActionIdentifier`

5. Copy the edited source to the clipboard

6. Convert the clipboard content to a pasteable action with the following shortcut (requires Actions app): https://www.icloud.com/shortcuts/49dfc2487764413a88c1329703dd76d1

7. Paste the converted action in the clipboard into a shortcut

You've now unlocked the hidden _Toggle Bold Text_ action
