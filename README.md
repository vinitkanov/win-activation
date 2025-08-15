# Microsoft Activation Scripts (MAS)

This project contains scripts to activate Windows and Office products using various methods. It is based on the work from [massgrave.dev](https://massgrave.dev).

## How to Use

There are two recommended methods to use these scripts:

### Method 1: PowerShell (Recommended)

1.  Open PowerShell as an administrator.
2.  Copy and paste the following command and press Enter:
    ```powershell
    irm https://get.activated.win | iex
    ```
3.  An activation menu will appear. Follow the on-screen instructions.

### Method 2: Traditional Download

1.  Download the repository as a ZIP file from [this link](https://github.com/massgravel/Microsoft-Activation-Scripts/archive/refs/heads/master.zip).
2.  Extract the ZIP file.
3.  Navigate to the `All-In-One-Version` folder.
4.  Run the `MAS_AIO.cmd` file.
5.  Follow the on-screen instructions.

## Activation Methods

Here is a summary of the available activation methods:

| Activation Type | Supported Product        | Activation Period                       |
| --------------- | ------------------------ | --------------------------------------- |
| HWID            | Windows 10-11            | Permanent                               |
| Ohook           | Office                   | Permanent                               |
| TSforge         | Windows / ESU / Office   | Permanent                               |
| KMS38           | Windows 10-11-Server     | Until 2038                              |
| Online KMS      | Windows / Office         | 180 days (renews automatically)         |

For more detailed information, please visit the official website: [massgrave.dev](https://massgrave.dev)
