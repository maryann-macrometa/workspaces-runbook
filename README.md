# Cloud Workspaces Runbook for Western Union

Macrometa Cloud Workspaces is redefining our approach to remote work and productivity. As a cloud-based virtual environment, it enables effective access to your work tools and business-specific applications directly from your browser. The service includes a suite of tools designed for high performance and security, including remote browser access and remote desktops on the edge.

## Objective
This runbook provides a comprehensive guide on how to use Western Union App and remote desktops from Macrometa Cloud Workspaces effectively. It covers everything from accessing the service to troubleshooting common issues and answers to frequently asked questions (FAQs).

## Using Cloud Workspaces

### Prerequisites

1. For **Windows 10**, download the latest stable **Chrome** browser.
2. For  **Windows 7** and **Windows 8.1**, download the latest supported Chrome browser.
3. For **Windows XP**, you need to install the **Supermium browser**. Follow these steps to download and install Supermium:

    a. Go to the [Supermium v.122 release page](https://github.com/win32ss/supermium/releases/tag/v122-r6) on GitHub
   
    b. Select and download the .exe file appropriate for your operating system architecture (32-bit or 64-bit).
   
    c. Locate the downloaded .exe file and double-click to start the installation. Follow the on-screen instructions to complete the installation process.
   
    d. During installation, select the "**Create shortcuts**" checkbox for easier access to the app after installation.


### Connecting to the workspace
Once your browser is installed on your device, 
1. Contact Macrometa support for the URL and valid authentication credentials to access your Cloud Workspace environment.
2. Open the browser and go to the provided URL. This URL connects you to your remote workspace and displays a login page.

3. Log in with appropriate credentials to your workspace.

After you’re connected, the **Workspaces** home screen is displayed. It has the following key services:
- **Remote Browser Acceleration (RBA)** - **Western Union App** for agents 
- **Virtual Desktop Interface(VDI)** - remote **Linux** and **Windows** desktops
- **VS Code**, a remote IDE for developers.



### Using VDI on Cloud Workspaces
Cloud Workspaces offer both persistent and non-persistent remote Windows and Linux desktops accessible through your browser, allowing you to perform tasks seamlessly as if on a local machine. These remote desktops support key peripherals such as **keyboard**, **mouse**, **printer**, **camera**, and **speaker**.

#### Prerequisite
Before using these remote desktops, download the required installer with these steps:
[Document the VDI installer]



#### Working with Windows
To start using the Windows desktop remotely, click **Windows Desktop** from the **Workspaces** menu. This action opens a new tab, establishing a secure connection and giving you full access to the remote Windows environment.


The Windows desktop interface provides essential control options to enhance your user experience and manage your session effectively:


1. **Display**
- **Fit**: Adjusts the screen display to fit within some dimensions of your local screen.
- **Full**: Expands the remote desktop to utilize your full screen, maximizing workspace.
- **Real**: Displays the remote desktop at its native resolution, allowing for detailed viewing.
2. **Ctrl+Alt+Del**: Opens a menu with account management and security options, including:
  - **Lock**: Secure your session.
  - **Sign Out**: Log out of the Windows session.
  - **Change Password**: Update your account password.
  - **Task Manager**: Access the Task Manager to monitor and manage running applications and processes.
3. **Meta icon**: Displays the Windows Start menu, providing quick access to applications and system settings.
4. **Toggle cursor kind**: Switch between different cursor types to suit your preferences or specific applications.
5. **Terminate session**: Closes the remote desktop session, ending your current connection to the virtual desktop safely.
These options help customize your remote desktop experience, manage your session, and navigate the Windows environment efficiently.

#### Working with Linux
To use the remote Linux desktop, click **Linux Desktop** from the **Workspaces** menu.  This action opens a new tab, establishing a secure connection and giving you full access to the remote Linux environment. From this point, you can begin your work just as you would on a local machine. Launch applications, access files, use the terminal or browser, configure your settings, e.t.c.



### Using RBA to access the Western Union App
From the **Workspaces** menu, click the **Western Union App**. The app opens up in a new tab within the remote browser.

#### Validating peripheral devices for RBA
The following peripheral devices are supported when accessing web apps in the remote browser: **signature pads**, **webcams**, **thermal printers**, **pin pad**, and **card readers**. 
To ensure these devices function correctly within your remote sessions:

1. Start by selecting the **Drivers and Updates** menu from the **Settings** menu on the **Workspaces** home screen. This downloads an installer (.exe file) to your device.
2. Run the installer to automatically configure all prerequisites needed for your peripherals.
3. Once the installation is complete, you can proceed to validate each peripheral device.
   
Once the drivers are installed, use the **Peripheral Validator** to check the functionality of your connected devices. 




Navigate to **Workspace Settings** and select **Peripherals Validator** to start the validation process for each device. It displays all the supported peripheral devices that can be validated.

##### Printer
To validate the printer, continue with the following steps:
1. Select **Printer** from the **Peripherals Validator** menu. It displays a coloured page to test the printer.

2. Click on **Test Printer** and add a virtual PDF printer to verify that it is accessible from the remote browser.
3. Select “**See more**..” from the **Destination** options on the print screen to check if the printer (Peripheral1-Printer) is listed. 

4. Select the printer and print the test page.

##### Signature Pad
To validate the signature pad, continue with the following steps:
1. Select **Signature Pad** from the **Peripherals Validator** menu. It displays a signature pad validator in a remote browser.

2. Connect your signature pad device and start signing. The signature is displayed in the input above.

#### Using the control bar

A control bar icon  appears on the left side of the screen for you to easily manage and interact with the remote browser.

To access the control bar,

- Click the control bar icon on the left side of the browser to access the menu.


Below is an overview of each menu on the control bar and how to use them to enhance your browsing experience.

1. **Drag viewport**: This setting allows you to move the remote browser window around the screen when minimized.
2. **Keys**: The keys menu provides on-screen buttons for essential control keys such as Control, Alt, Tab, and the Esc key. This functionality is especially handy for mobile device users who don't have access to a full keyboard.
3. **Clipboard**: The clipboard feature allows text transfer between your local device and the remote browser. Text copied within the remote browser appears in this panel for easy access. This is not compulsory for the Chrome browser, as it has native clipboard integration that handles text efficiently.
4. **Fullscreen**: Full screen maximizes the remote browser to fill your entire screen, providing an immersive and distraction-free browsing experience. Use the Esc key to exit fullscreen mode.
5. **USB**: The USB menu displays all devices connected to your local device via USB. To connect a device to the remote browser, select it from the list and click Connect.
6. **Display**:  This menu allows you to manage multiple monitors efficiently. Click the Display menu to add, remove, and arrange screens. New screens open in separate browser windows, which you can position on your local monitors. Use the Display menu to match the on-screen arrangement to your physical setup and adjust positions and sizes as needed.


7. **Settings**: The Settings menu lets you customize your remote browser further. Here, you can adjust various aspects to tailor the browser to your preferences and optimize your user experience.

    a. **View-only**: This option restricts the remote browser to a read-only mode, preventing any write operations. Users can browse and view content without being able to modify or interact with elements.
  
    b. **Clipboard Up**: Allows users to copy text from their local device and paste it into the remote browser.
  
    c. **Clipboard Down**: Enables copying content from the remote browser and pasting it onto your local device.
  
    d. **Clipboard Seamless**: This feature facilitates copying and pasting between your local device and the remote browser without noticeable delays or additional steps.
  
    e. **Prefer Local Cursor**: Prioritizes using the local machine's cursor for display and interaction, providing a more consistent user experience.
  
    f. **Translate keyboard shortcuts**: Automatically converts local keyboard shortcuts to the corresponding shortcuts in the remote browser, ensuring they function correctly within the remote environment.
  
    g. **Enable Performance Stats**: This option displays real-time performance metrics of the remote browser at the top right corner of the screen. These metrics include an FPS counter, along with network and CPU stats, where each stat shows the current value and an averaged value over time. A lower value indicates higher resource constraints, helping to identify if performance bottlenecks are due to server-side CPU or network issues.
  
    h. **Enable Pointer Lock**:  Constrains the cursor within the remote browser window, providing better control during use. To release the cursor, press the escape key.
  
8. **Audio**: Click the audio icon    to enable or disable audio output from the remote browser. 

## Troubleshooting and FAQs
Here are some common issues, and steps to resolving them.

### Why can’t I access workspaces?
This may result from reasons like an incorrect URL or browser incompatibility. To resolve this:
- Confirm your system meets the system requirements
- Check the accuracy of your Workspaces URL.
- Contact Macrometa

### Why am I unable to use my peripheral devices(printer, webcams, card reader)

Peripheral devices need to be validated before being used in workspaces. However, download and install the drivers before validating your devices.

### What should I do if my team experiences high latency or slow performance accessing the remote workspaces?

Macrometa workspaces require a minimum network bandwidth to perform optimally. To resolve slow performance:
- Verify the network connection and bandwidth quality.
- Review network congestion and possible throttling at the local ISP level.
