# HelloWorldLab

Android lab app. Enter a name, tap "Click Me", and the greeting updates.

## Run

Open in Android Studio and run on an emulator or device (min SDK 30).

```bash
./gradlew installDebug
```

## What it does

- `MainActivity.kt` — reads the name field and sets the TextView to `Hi, {name}` on button click
- `activity_main.xml` — TextView, EditText, and Button laid out with ConstraintLayout
