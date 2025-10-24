# Pylogger

[Pylogger](https://github.com/kyotinho/PyLogger) is an open-source, fully customizable and light-weight Keylogger made entirely in python.

> [!IMPORTANT]
> Pylogger is 100% free for use and it's use is entirely in responsability of the user

## Features

- **Lightweight**: Minimal resource usage and efficient performance
- **Automatic Log Rotation**: Creates new .txt files every 120 seconds
- **Customizable Target Path**: You choose the path where the logger will save the txt
- **Stealth Operation**: Invisible executable that runs discreetly in task manager
- **Debugging Tools**: Includes debugger executable to verify application functionality
- **Open Source**: Fully transparent codebase for customization and verification
- **Free**: 100% free with no limitations for the user
- **Well-optimized text format** The TXT has a simple and easy to understand formatting

## Installation

1. Download the latest release from the [releases page](https://github.com/kyotinho/PyLogger/releases)
2. Extract the files to your desired location
3. Run the application according to your needs (can be any of the three apps)

## Usage

### Main Application
- Run the invisible executable for normal operation
- Application runs silently in the background
- Automatically creates timestamped .txt files every 120 seconds

### Debug Mode
- Use the debugger executable to test and verify functionality
- Monitor application behavior and log generation
- Useful for troubleshooting and development

### Debug Mode with Del Kill-Switch
- The same thing as the Debugger but with a switchable feature that enables to close (or not) the app using the Del key on your keyboard

## File Structure

```
Pylogger/
DebugDelSwitch.spec
Keylogger.spec
KeyloggerDebug.spec
├── build # -- Main Python Builds for the .exes
├── dist # -- Where the .exes are located
│   ├── DebugDelSwitch.exe # -- Debug executable with Del Switch (not hidden in the task manager)
│   ├── KeyLoggerDebug.exe # -- Debug executable
│   ├── KeyLogger.exe # -- Main executable (will be hidden in the task manager)
├── saves # -- The source code for every file
│   ├── baselogger.py # -- Source code for the Main executable
│   ├── debug.py # -- Source code for the Debug executable
│   ├── debugdelswitch.py # -- Source code for the Debug executable with Del Switch
│   └── ...
└── README.md
```

## Log Files

- Logs are saved as plain text files (.txt)
- New file created every 120 seconds
- Files include timestamp in filename for easy organization
- All keystrokes are recorded in chronological order

## Legal Disclaimer

This software is provided for educational, testing, and legitimate monitoring purposes only. Users are solely responsible for complying with all applicable laws and regulations in their jurisdiction. Always ensure you have proper authorization before monitoring any system.

## Contributing

Contributions are welcome! Please feel free to submit pull requests, report issues, or suggest new features.

## License

This project is open source and available under the [MIT License](LICENSE).
