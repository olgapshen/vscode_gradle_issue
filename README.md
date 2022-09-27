# Sample project for submit issue

Sample project for submit issue to [vscode-gradle][1].

In the current state we have follow error:

> unable to resolve class ru.valkovesi.helpers.FileSystemHelper
> @ line 21, column 8.

If we will put content of `gradle/db.gradle` inside `build.gradle`
instead of:

```
apply from: "$projectDir/gradle/db.gradle"
```

and remove `gradle/db.gradle`, we get rid of the error.

[1]: https://github.com/microsoft/vscode-gradle/issues
