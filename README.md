#Readme

This utility runs checks of various SNMP functions from a LAMP server to an IP address.   Allows loading of MIB files, and checking each PHP SNMP function individually. 

##Prerequistes

This has been tested on PHP 5.3, 5.4.  This requires the php_snmp extension to be loaded. 

##Configuration

Place index.php (or rename as needed) in web directory.  Mibs will be loaded from a folder in the same directory, if it exists. 
