## MicroCode Studio Plus 5.0.12: A Powerful IDE for PICBASIC PRO

 
![Microcode Studio Plus 5 0 12](https://download.amd.com/OneTrust/202303.1.0a/consent/17a54836-920d-4fc2-a8f6-3f4c299371d1/c9e5990e-f8e7-47d3-a4ef-5fd1a9e6f449/logos/522af4e3-8eb6-419a-ab34-33424f162acd/b5753b26-66ca-48b2-9cf8-f49f6f86d4fc/8ea1ec5d-9e72-477e-af81-45810eb32c32/AMD-Logo-700x394.png)

 
# MicroCode Studio Plus 5.0.12: A Powerful IDE for PICBASIC PRO
 
MicroCode Studio Plus is a visual Integrated Development Environment (IDE) with In Circuit Debugging (ICD) capability designed specifically for microEngineering Labs PICBASIC PROâ¢ compiler. It allows you to write, edit, compile, and debug your PICBASIC PRO code with ease.
 
## Microcode Studio Plus 5 0 12


[**DOWNLOAD**](https://searchdisvipas.blogspot.com/?download=2tKFn2)

 
The latest version of MicroCode Studio Plus, 5.0.12, was released on October 2021 and is compatible with Windows XP/7/8/10/11 and PICBASIC PRO 3.0.0.0 or higher. It includes many features and improvements, such as:
 
- More ICD Model Files than the standard version
- An ICD Model Creator Wizard - create your own ICD Models!
- MicroCode Loader Software - upload your code to your PIC microcontroller without a programmer
- Syntax highlighting, code folding, auto-completion, code templates, and more
- Integrated simulator, oscilloscope, logic analyzer, and serial monitor
- Support for multiple compilers and devices
- And much more!

If you are looking for a powerful, user-friendly, and affordable IDE for your PICBASIC PRO projects, you should definitely check out MicroCode Studio Plus 5.0.12. You can download it from the developer's website[^2^] or purchase it from Mecanique[^1^] for only Â£36.00 (ex VAT).
 
MicroCode Studio Plus is a trademark of Mecanique. PICBASIC and PICBASIC PRO are trademarks of microEngineering Labs.
  
In this article, we will show you how to use MicroCode Studio Plus 5.0.12 to create a simple PICBASIC PRO project and debug it with the ICD feature. For this example, we will use a PIC16F877A microcontroller and a LED connected to pin RB0.
 
## Step 1: Create a new project
 
Open MicroCode Studio Plus and click on File > New > Project. Give your project a name and a location and click OK. A new project window will open with a blank code editor.
 
## Step 2: Write your code
 
Type the following code in the code editor:
 `
' PIC16F877A Configuration Bit Settings
' CONFIG
__CONFIG _FOSC_HS & _WDTE_OFF & _PWRTE_ON & _BOREN_OFF & _LVP_OFF & _CPD_OFF & _WRT_OFF & _DEBUG_ON & _CP_OFF
' Define device and clock frequency
DEFINE OSC 20
' Define LED pin
LED VAR PORTB.0
' Main loop
DO
    ' Toggle LED state
    LED = ~LED
    ' Wait 500 ms
    PAUSE 500
LOOP
` 
This code will configure the device settings, define the LED pin, and toggle the LED state every 500 ms.
 
## Step 3: Compile your code
 
Click on Project > Compile or press F9 to compile your code. If there are no errors or warnings, you will see a message saying "Compile successful" in the output window. You can also view the generated assembly code and hex file by clicking on View > Assembly Listing or View > Hex File.
 
## Step 4: Debug your code
 
Connect your PIC microcontroller to your PC using a suitable programmer or debugger. Make sure the device is powered and the MCLR pin is pulled high. Click on Debug > Start Debugging or press F8 to start the ICD session. A new window will open with the ICD toolbar and the ICD model of your device.
 
You can use the ICD toolbar to control the execution of your code, set breakpoints, watch variables, modify registers, and more. You can also view the status of your device pins, memory, stack, and peripherals in the ICD model window.
 
To test your code, click on Run > Run or press F5 to run your code. You should see the LED on your device blinking at a regular interval. You can also pause, step, or reset your code using the ICD toolbar buttons.
 
## Conclusion
 
MicroCode Studio Plus 5.0.12 is a powerful IDE for PICBASIC PRO that offers many features and tools to make your development process easier and faster. With the ICD feature, you can debug your code in real time and find and fix errors quickly. You can download MicroCode Studio Plus 5.0.12 from the developer's website or purchase it from Mecanique for only Â£36.00 (ex VAT).
 0f148eb4a0
