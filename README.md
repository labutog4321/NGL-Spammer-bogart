
# NGL Spammer

![NGL Spammer Logo](logo.png)

Welcome to the **NGL Spammer!** This is a simple script that sends questions to the NGL API quickly and logs the responses in real-time. Let’s dive in!

---

## Features

- **⚡ Fast Questions**: Sends spam questions to the NGL API at regular intervals.
- **📊 Real-Time Logs**: Instantly logs successful and failed requests.
- **✅ Success Counts**: Displays the counts of successful and failed requests.
- **🛠️ Easy Customization**: Customize the questions and settings easily.

---

## Installation

### What You Need

Make sure you have **Node.js** and **npm** installed on your computer.

---

### Steps to Set Up

1. **Clone the repo:**
   ```bash
   git clone https://github.com/JrDevProgect/NGL-Spammer.git
   cd NGL-Spammer
   ```

2. **Install the packages:**
   ```bash
   npm install
   ```

3. **Edit the config:**
   - Open `config.json` and set your username and questions.

4. **Run the script:**
   ```bash
   node index.js
   ```

---

## How to Use

1. Open your web browser and go to `http://localhost:3000`.
2. Watch the logs update in real-time as questions are sent.
3. Check how many requests succeeded and how many failed.

---

## Configuration

Change the settings in `config.json`:

```json
{
    "interval": 2,  // Time in seconds between requests
    "username": "your_username",  // Your username for NGL
    "questions": [
        "What’s up?",
        "How are you?",
        "Tell me something funny!"
    ]
}
```

---

## Deploying on Render

1. **Create a Render Account:**
   - Go to [Render](https://render.com) and sign up for a free account.

2. **Create a New Web Service:**
   - Click on the "New" button and select "Web Service."
   - Connect your GitHub account and select the repository you just created.

3. **Configure Your Service:**
   - Set the **Name** for your service.
   - Choose the **Region** (e.g., US).
   - For the **Environment**, select **Node**.
   - Set the **Build Command** to:
     ```bash
     npm install
     ```
   - Set the **Start Command** to:
     ```bash
     node index.js
     ```

4. **Deploy:**
   - Click on "Create Web Service" to deploy your script. Wait for the process to finish.

5. **Access Your Script:**
   - Once deployed, Render will provide you with a URL to access your script.

---

## Keeping It Uptime with Uptime Robot

1. **Create an Uptime Robot Account:**
   - Go to [Uptime Robot](https://uptimerobot.com) and sign up for a free account.

2. **Add a New Monitor:**
   - Click on "Add New Monitor."
   - Select the **Monitor Type** as "HTTP(s)."

3. **Configure Your Monitor:**
   - Enter a **Friendly Name** for your monitor (e.g., NGL Spammer).
   - In the **URL** field, enter your Render script's URL.
   - Set the **Monitoring Interval** to your preference (e.g., 5 minutes).

4. **Save the Monitor:**
   - Click "Create Monitor." Uptime Robot will now check your script at the interval you set.

---

## License

This project is under the MIT License. Check the [LICENSE](LICENSE) file for more info.

---

## Owner

This project is maintained by [JrDev06](https://www.facebook.com/profile.php?id=100091592152325). Feel free to reach out!

---

### Thank You for Checking Out NGL Spammer!

We hope you enjoy using this script! If you have any questions, feel free to contact the owner.
