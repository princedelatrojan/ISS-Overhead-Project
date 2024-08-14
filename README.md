

---

# ISS Overhead Notifier

A Python script that tracks the International Space Station (ISS) and notifies you when it's overhead based on your location. Perfect for space enthusiasts to easily spot the ISS in real time.

## Features

- Tracks the ISS position in real time.
- Notifies when the ISS is overhead at your location.
- Simple and easy-to-use Python script.

## Prerequisites

- Python 3.x
- `requests` library

Install the required library using pip:

```bash
pip install requests
```

## Usage

1. Clone this repository:

```bash
git clone https://github.com/yourusername/ISS-Overhead-Notifier.git
cd ISS-Overhead-Notifier
```

2. Update your location coordinates in the script (`latitude`, `longitude`).

3. Run the script:

```bash
python iss_notifier.py
```

## How It Works

- The script fetches the current position of the ISS using the [Open Notify API](http://open-notify.org/Open-Notify-API/ISS-Location-Now/).
- It compares the ISS position with your location to determine when the ISS is overhead.
- A notification is sent when the ISS is visible from your location.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

