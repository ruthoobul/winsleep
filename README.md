# WinSleep

WinSleep is a Python program designed to schedule sleep and wake times for Windows systems to save energy and enhance longevity. The program automates the process of putting the system to sleep at a specified time and provides a reminder to ensure the system can wake up at a set time.

## Features

- Automatically schedules sleep for the system at specified times.
- Provides details on when the system should wake (requires BIOS or additional configurations).
- Designed to enhance system longevity by reducing power usage during non-peak hours.

## Prerequisites

- Windows Operating System
- Python 3.x installed on your system
- Administrator privileges (required for adjusting system privileges)

## Installation

1. Clone the repository or download the `WinSleep.py` file.
2. Ensure you have Python installed on your system.
3. Run the program with administrator privileges.

## Usage

1. Open a terminal or command prompt with administrator privileges.
2. Navigate to the directory containing `WinSleep.py`.
3. Run the script using Python:

   ```bash
   python WinSleep.py
   ```

4. The program will inform you of the scheduled sleep and wake times.

## Notes

- The program assumes the system supports wake timers. Ensure these are configured in the system BIOS or through a compatible tool.
- The default sleep time is set to 11:00 PM and wake time to 7:00 AM. Modify these times in the script as needed.
- Adjusting system privileges is necessary for putting the system to sleep programmatically.

## Disclaimer

Use this program responsibly. Make sure important tasks are saved and closed before the system enters sleep mode. The authors are not responsible for any data loss or issues arising from the use of this program.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.