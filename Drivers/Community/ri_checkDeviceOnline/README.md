### Project Information:
iTest Ping Driver  
  
___
This driver uses the 'management' interface, where getPorts and getProperties methods are called. Discover function is supported, but really only returns a 'success' verdict, and no information is really discovered. The polling mechanism invokes the getPorts method which pings the ip address specified in the 'ipAddress' property. This driver works both on Linux and Windows agents  
  
___
<b>Tags:</b> Driver, Management  
  
___
1 Procedure Library in project://ri_checkDeviceOnline
### Library: project://ri_checkDeviceOnline/checkDeviceOnline.fftc
___
### getProperties
### getPorts
