
# Meeting Room Calendar Viewer

This project is a simple GitHub Pages-compatible webpage that displays an Outlook calendar using an online ICS link and the Open Web Calendar service.

## 📁 Project Structure

- `index.html`: Main HTML file that loads and displays the calendar.
- `config.js`: Stores the ICS calendar URL as a JavaScript variable.

## 🔧 How It Works

1. `config.js` defines a variable `calendarUrl` containing the ICS calendar link.
2. `index.html` loads `config.js` and uses the value of `calendarUrl` to embed the calendar via Open Web Calendar.
3. The calendar is displayed in an iframe and automatically updates based on the ICS feed.

## 🚀 Deployment Instructions

1. Create a GitHub repository and upload `index.html` and `config.js` to the root directory.
2. Go to **Settings → Pages** in your repository.
3. Under **Source**, select the `main` branch and root (`/`) folder.
4. Save and GitHub will provide a public URL to access your calendar viewer.

## 🔄 Updating the Calendar

To change the calendar being displayed, simply edit the `calendarUrl` value in `config.js`:

```javascript
const calendarUrl = "https://your-new-calendar-link.ics";
```

Save and commit the change to GitHub, and your webpage will automatically reflect the new calendar.

## 🌐 Example Usage

```
https://your-username.github.io/meeting-room-calendar/
```

## 📌 Notes

- Make sure your ICS link is publicly accessible.
- If your ICS link starts with `webcal://`, replace it with `https://`.

