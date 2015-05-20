OpenVPN authentication plugin you can use to authorize your Windows users. Copy the OpenVPNSSPI.dll file to your OpenVPN\bin folder and add following lines to your server configuration:

plugin "C:\\Program Files\\OpenVPN\\bin\\OpenVPNSSPI.dll" login


You can than turn the client certificates off (although it's not recommended):

client-cert-not-required


Tested on Windows 2008 Server