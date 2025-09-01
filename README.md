
# Focus404 - Pomodoro Timer

A simple Pomodoro timer application built with Astro.

## Overview

Focus404 is a web-based Pomodoro timer designed to help you improve focus and productivity. It implements the core principles of the Pomodoro Technique, alternating between work intervals and short breaks.

## Features

*   **Timer Display:** Clear display of the remaining time in the current phase (Work, Break, Super Break).
*   **Start/Pause:** Easily start and pause the timer.
*   **Reset:** Reset the timer to the beginning of the current phase.
*   **Skip:** Skip the current phase and move to the next.
*   **Finish:** Immediately end the current session and reset the timer.
*   **Visual Stage Indicators:** Track your progress through work cycles with visual indicators.
*   **Configurable Timings:** Easily adjust work, break, and super break durations.
*   **Icon Integration:** Clear visual cues for each action using SVG icons.

## Project Structure

```text
/
├── public/
│   └── icons/         # SVG icons for the timer controls
│       ├── play.svg
│       ├── pause.svg
│       ├── reset.svg
│       ├── finish.svg
│       └── skip.svg
├── src/
|   | 
│   ├── assets/
│   │
│   ├── components/
│   │   └── Pomodoro.astro  # The main Pomodoro timer component
│   ├── layouts/
│   │   └── Layout.astro    # Base layout for the page
│   ├── pages/
│   │   └── index.astro     # The main page displaying the Pomodoro timer
│   └── styles/
│       └── global.css      # Global styles for the application
├── astro.config.mjs       # Astro configuration file
├── package.json           # Project dependencies and scripts
└── README.md              # This file
```

## Dependencies

*   Astro
*   Tailwind CSS

## Setup

1.  **Clone the repository:**

    ```bash
    git clone <repository_url>
    cd focus404
    ```

2.  **Install dependencies:**

    ```bash
    npm install # Or yarn install or pnpm install
    ```

## Usage

1.  **Start the development server:**

    ```bash
    npm run dev # Or yarn dev or pnpm dev
    ```

    This will start the Astro development server. Open your browser and navigate to `http://localhost:4321` (or the address shown in the console) to view the Pomodoro timer.

2.  **Build for production:**

    ```bash
    npm run build # Or yarn build or pnpm build
    ```

    This will create an optimized production build of the application in the `dist` directory.

## Customization

You can customize the timer durations and other settings by modifying the `Pomodoro.astro` component:

*   `workTime`: Duration of work intervals (in seconds).
*   `breakTime`: Duration of break intervals (in seconds).
*   `superBreakTime`: Duration of super break intervals (in seconds).
*   `numStages`: Number of work/break cycles before a super break.

## Contributing

Contributions are welcome! If you find a bug or have a suggestion, please open an issue or submit a pull request.

## License

[Choose a license and add it here]