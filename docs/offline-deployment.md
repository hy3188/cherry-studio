# Offline Deployment Guide

This guide provides detailed instructions for deploying the application in offline mode.

## Download Instructions
1. Navigate to the [Releases page](https://github.com/hy3188/cherry-studio/releases).
2. Locate the latest release suitable for offline deployment.
3. Download the appropriate offline version of the package.

## Installation Steps
### For Devices with Network
1. Make sure your device has access to the internet.
2. Follow the usual installation instructions as provided in the documentation.

### For Devices without Network
1. Download the package as mentioned in the Download Instructions.
2. Transfer the downloaded file to your offline device using USB or any other means.
3. Open a terminal and navigate to the directory containing the offline package.
4. Run the installation command:
    ```bash
    sudo dpkg -i package_name.deb
    ```
5. Resolve any dependencies that may be required by running:
    ```bash
    sudo apt-get install -f
    ```

## Verification Commands
Once the installation is complete, verify that the application is installed successfully by running:
```bash
your-application --version
```

## System Requirements
- OS: Ubuntu 20.04+  
- Architecture: ARM64

## Common FAQs
1. **What if I encounter dependency issues?**  
   - Ensure all dependencies are also downloaded and available on the offline device.

2. **Can I use this guide for other operating systems?**  
   - This guide is specifically for Ubuntu 20.04+ ARM64. Other systems may have different requirements.

## Supported Platforms
- Ubuntu 20.04+ (ARM64)
- Any platform that can run the ARM64 architecture.

---

_Note: Always check the Release page for the latest information and updates regarding offline deployment._