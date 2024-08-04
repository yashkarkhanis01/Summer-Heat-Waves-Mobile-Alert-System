<h1 align="center">Summer Heat Waves Mobile Alert System 🌡️</h1>
<p align="center">
  <a href="https://github.com/yashkarkhanis01/Summer-Heat-Waves-Mobile-Alert-System">
    <img alt="GitHub Repository Stars Count" src="https://img.shields.io/github/stars/yashkarkhanis01/Summer-Heat-Waves-Mobile-Alert-System?style=social" />
  </a>
  <a href="https://github.com/yashkarkhanis01/Summer-Heat-Waves-Mobile-Alert-System">
    <img alt="Github Repository Fork Count" src="https://img.shields.io/github/forks/yashkarkhanis01/Summer-Heat-Waves-Mobile-Alert-System?style=social">
  </a>
  <a href="https://github.com/yashkarkhanis01/Summer-Heat-Waves-Mobile-Alert-System">
    <img alt="Number of Contributors" src="https://img.shields.io/github/contributors/yashkarkhanis01/Summer-Heat-Waves-Mobile-Alert-System?style=social">
  </a>
</p>
<h3 align="center">Get Notified About Heat Waves Through SMS</h3>

<h3 align="center">⭐ Don't forget to star this repository! ⭐</h3>

## ❓ About

The Summer Heat Waves Mobile Alert System is a Python-based project designed to monitor temperature data and send SMS alerts when a heatwave is detected. This system uses historical temperature data to identify heatwaves and utilizes the Twilio API to send notifications to users.

## 📦 Requirements

1. **Python Libraries**:
    ```bash
    pip install pandas twilio
    ```

2. **CSV File**:
    - Ensure you have a CSV file named `historical_temperature_data.csv` containing your temperature data.

3. **Twilio Account**:
    - Sign up for a [Twilio account](https://www.twilio.com/).
    - Obtain your Account yash and Auth Token from the Twilio Console.

## 🚀 How to Use

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yashkarkhanis01/Summer-Heat-Waves-Mobile-Alert-System.git
    cd Summer-Heat-Waves-Mobile-Alert-System
    ```

2. **Set Up Twilio**:
    - Replace `'your_account_yash'` and `'your_auth_token'` with your actual Twilio Account yash and Auth Token in the `send_sms` function.

3. **Run the Script**:
    ```bash
    python heatwave_alert.py
    ```

## ⚡ Code Explanation

The core functionalities of the system are implemented in the following functions:

### `detect_heatwaves(data, threshold=30, consecutive_days=3)`

This function detects heatwaves in the temperature data. A heatwave is defined as temperatures exceeding a specified threshold for a given number of consecutive days.

### `send_sms(to, message)`

This function sends an SMS alert using the Twilio API. It takes the recipient's phone number and the message to be sent as inputs.

## ❤️ Contributors:
<br>
<a href="https://github.com/yashkarkhanis01/Summer-Heat-Waves-Mobile-Alert-System/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=yashkarkhanis01/Summer-Heat-Waves-Mobile-Alert-System&&max=817" />
</a>
</br>
