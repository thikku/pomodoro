# Modern Pomodoro Timer

This is a simple yet modern Pomodoro timer web application designed to help you manage your time effectively by breaking down work into focused intervals separated by short and long breaks.

## Features
- Pomodoro Sessions: Set a dedicated time for focused work (default: 25 minutes).
- Short Breaks: Take quick breaks after each Pomodoro session (default: 5 minutes).
- Long Breaks: Enjoy a longer break after every four Pomodoro sessions (default: 15 minutes).
- Automatic Mode Switching: The timer automatically transitions between Pomodoro and break modes upon completion.
- Start, Pause, and Reset Controls: Full control over the timer's operation at any time.
- Visual Feedback: Clear indication of the active mode and status messages.
- Sound Alarm: A subtle sound plays when a session ends to notify you.
- Responsive Design: The interface adapts to various screen sizes, ensuring a good experience on desktop and mobile devices.
- Modern Aesthetics: A clean, dark-themed design with smooth transitions and rounded elements, powered by Tailwind CSS.

## Technologies Used
- HTML5: For the basic structure of the web page.
- CSS3 (Tailwind CSS CDN): For responsive and modern styling.
- JavaScript: For all the timer logic and interactivity.
- Tone.js (CDN): A web audio framework used to generate the alarm sound.

## How to Use
- Open the Application: Simply open the index.html file in your web browser.
- Select a Mode:
	Click "Pomodoro" to start a work session.
	Click "Short Break" for a brief pause.
	Click "Long Break" for an extended rest.
- Start the Timer: Click the "Start" button to begin the countdown for the selected mode.
- Pause/Resume: Click the "Pause" button (which appears after starting) to temporarily stop the timer. Click "Start" again to resume.
- Reset the Timer: Click the "Reset" button to stop the current timer and set it back to its initial duration for the current mode.
- Automatic Transitions: When a Pomodoro session ends, the timer will automatically switch to a short break. After every 4 Pomodoros, it will switch to a long break. After any break, it will return to the Pomodoro mode and automatically start.
- Sound Notification: An alarm sound will play when any timer session concludes.

## Customization
You can easily adjust the durations of the Pomodoro, short break, and long break sessions by modifying the `POMODORO_DURATION`, `SHORT_BREAK_DURATION`, and `LONG_BREAK_DURATION` constants in the JavaScript code.// Durations in seconds

```bash
const POMODORO_DURATION = 25 * 60; // 25 minutes
const SHORT_BREAK_DURATION = 5 * 60;  // 5 minutes
const LONG_BREAK_DURATION = 15 * 60; // 15 minutes
```

Future Enhancements (Ideas)User-configurable durations.Task list integration.Notification API integration for desktop notifications.More diverse alarm sounds.Progress visualization (e.g., a circular progress bar).
