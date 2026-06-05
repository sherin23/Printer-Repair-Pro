# 🖨️ Printer Repair Pro

A PowerShell-based printer diagnostics and repair utility for Windows.

Created by **Sherin Sunny**

## Features

* Detect installed printers
* Detect installed printer drivers
* Restart Print Spooler automatically
* Clear stuck print jobs
* Trigger Windows Update scan
* Detect Plug-and-Play printer devices
* Generate detailed HTML reports
* Generate repair logs
* Set default printer
* Print a test page
* Export diagnostics for troubleshooting

## Supported Operating Systems

* Windows 10
* Windows 11
* Windows Server 2019
* Windows Server 2022

## Project Structure

```text
PrinterRepairPro/
├── PrinterRepairPro.ps1
├── RunPrinterRepair.bat
├── Logs/
├── Reports/
└── README.md
```

## Installation

Clone the repository:

```powershell
git clone https://github.com/yourusername/PrinterRepairPro.git
cd PrinterRepairPro
```

Or download the ZIP and extract it.

## Usage

### Option 1: Batch Launcher

Run as Administrator:

```cmd
RunPrinterRepair.bat
```

### Option 2: PowerShell

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force
.\PrinterRepairPro.ps1
```

## Generated Output

### Logs

```text
Logs/
└── PrinterRepair_YYYYMMDD_HHMMSS.log
```

### Reports

```text
Reports/
└── PrinterReport_YYYYMMDD_HHMMSS.html
```

The report includes:

* System Information
* Installed Printers
* Installed Printer Drivers
* Plug-and-Play Printer Devices
* Diagnostic Information

## Example Workflow

1. Run the tool as Administrator
2. Printer Spooler is restarted
3. Stuck print jobs are removed
4. Printers and drivers are enumerated
5. Windows Update scan is triggered
6. HTML diagnostic report is generated
7. Test page is printed

## Screenshots

### HTML Report

*Add screenshot here*

### Console Output

*Add screenshot here*

## Roadmap

* [ ] Windows Forms GUI
* [ ] Driver Health Analysis
* [ ] Network Printer Diagnostics
* [ ] PDF Report Generation
* [ ] Automatic Driver Validation
* [ ] Enterprise Reporting Dashboard
* [ ] Multi-Computer Support

## Limitations

This tool does not automatically download vendor-specific drivers from manufacturers such as:

* HP
* Canon
* Epson
* Brother
* Xerox
* Ricoh
* Kyocera

Some printers may still require official vendor driver packages.

## Contributing

Pull requests and feature suggestions are welcome.

## License

MIT License

## Author

**Sherin Sunny**

If this project helps you, consider starring ⭐ the repository.
