# ⏳ Hackathon Countdown Timer

A lightweight and visually engaging countdown timer designed for programming contests and hackathons.

## 🚀 Features

- Real-time countdown with 1-second updates
- Circular animated progress indicators (SVG-based)
- Automatic status display:
  ⏳ Waiting for start
  🚀 Competition running
  ✅ Competition finished
- Simple configuration (start time + duration)
- No dependencies (pure HTML, CSS, JavaScript)

## 📦 Setup

1. Clone this repo

   git clone <https://github.com/houcine1amraoui/countdown-timer>

2. Open the index.html file in your browser

## ⚙️ Configuration

All configuration is done inside the script section:

    const startDate = new Date("April 22, 2026 14:00:00").getTime();
    const duration = 2 * 60 * 60 * 1000; // 2 hours

### 🔧 Parameters

- startDate → Competition start date & time
- duration → Competition duration in milliseconds

⏱ Examples

3-hour contest:

    const duration = 3 * 60 * 60 * 1000;

90-minute contest:

    const duration = 90 * 60 * 1000;

## 🖥️ Usage in Contest

- Display on a projector or shared screen
- Open in full-screen mode (F11)
- Ensure system clock is correct
- Optionally host on a local server for multiple displays

## 🎨 Customization

You can easily customize:

Title:

    <h1>Hackathon 2026</h1>

Subtitle:

    <h2>Competition Time Remaining</h2>

Colors (CSS):

    .progress {
        stroke: #00ffd5;
    }

Background:

    background: url("faculty.jpg") center/cover no-repeat;

## ⚠️ Notes

- Time is based on the client machine clock
- No backend or synchronization included
- For strict environments, ensure all machines use the same time source

## 📄 License

Free to use for educational and contest purposes.
