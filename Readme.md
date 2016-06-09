
The commands in this module are designed to make it easier to find machine- based certificates that you can use to verify the identity of a server. Often these certificates are used in Desired State Configuration to encrypt passwords or perform other sensitive operations. Typically you need to get the thumbprint from the certificate.

The two commands in the module are very similar, except that one of them will export a copy of the certificate, usually to a local directory. The commands rely on commands from the PKI module for certificate testing and export.

Since the commands rely on PowerShell remoting, many of the parameters are from Invoke-Command.

The commands were originally described and used in my DSC courses I created for Pluralsight.

https://www.pluralsight.com/courses/powershell-desired-state-configuration-fundamentals
https://www.pluralsight.com/courses/advanced-powershell-dsc

Learn more about PowerShell:
http://jdhitsolutions.com/blog/essential-powershell-resources/

  
  
