# Foreground

This library makes it easy to check if your app is in the foreground or background.

## Usage

```
// app is the Application object

Foreground.init(app);

// check state manually
Foreground.get().isForeground();

// register callbacks
Foreground.get().addListener(some listener);

```