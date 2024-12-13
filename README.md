
##Bufferstack.IO Universal OPCUA Server Shareware

Welcome to the Bufferstack.IO Universal OPCUA Server Shareware! This application 
allows you to create an OPC UA server with support for Modbus devices. 
It is designed for use with Industrial Devices like PLC and SCADA software.


##Application Details

Product Name: Bufferstack.IO Universal OPCUA Server Shareware
Version: 1.0.1
Developer: Bufferstack.IO
License: Shareware - DO NOT SELL, DO NOT DISTRIBUTE


##Features

1. OPC UA Server
   - Fully compliant OPC UA server implementation.
   - Customizable server name and branding.
   
2. Modbus Integration
   - Read and write data from Modbus TCP devices.
   - Polling mechanism to retrieve data periodically.
   - Configurable address space for each Modbus device.

3. Licensing Controls
   - Shareware version with Unlimited Modbus Device Access.
   - One-hour runtime limitation.
   

##Requirements

- Minumum Windows 10 wirh administrator access
- Modbus devices (TCP/IP support required)
- An OPC UA client for testing (e.g., UAExpert, Prosys)


##Installation

Run the installer and check for the instructions. Disable firewall and antivirus
if any.


##Configuration

1. Edit the config.conf file to set up the OPC UA server and Modbus devices.
2. Key settings include:
   - OPC UA server port and resource path.
   - Modbus device host, port, unit ID, and polling rate.
3. Save the changes to config.conf.
4. Run network-configurator.exe provided in install directory to configure the network 
   that will be used to connect to the modbus device(s). 


##Running the Application

1. Start the application by running:
  B10-opcua-server-shareware from cli directory you installed it or Program Manager

2. The server will:
   - Start listening on the configured OPC UA port.
   - Connect to Modbus devices and expose their data in the OPC UA address space.
   - Log connection and communication data to daemon.log in the local directory

3. Use an OPC UA client to connect to the server. 


##Limitations

- Runtime is limited to one hour per session.
- Redistribution, sale, or modification is strictly prohibited.
- This shareware version is for evaluation purposes only.


##Support

For support or inquiries, please contact Bufferstack.IO at:
Website: http://bufferstack.io
Email: harshad@bufferstack.io


##License Agreement

This application is provided as shareware for evaluation purposes. By using this 
application, you agree to the following terms:

1. Redistribution, sale, or modification of this application is strictly prohibited.
2. This application is provided "as-is" without any guarantees or warranties.
3. Bufferstack.IO Analytics Technology LLP, Pune is not liable for any damages or 
   losses arising from the use of this application.


##Acknowledgments

Our wonderful Beta Test Team and Automation Partners

