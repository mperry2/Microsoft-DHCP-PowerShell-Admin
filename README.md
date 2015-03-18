# Microsoft-DHCP-PowerShell-Admin

This is a PowerShell module for the administration of Microsoft DHCP.

Since there is no .NET API, I had to use netsh (with its inherent limitations) to handle everything I wanted to do in DHCP. With that said, this module is not an exhaustive translation of every command available in netsh for DHCP, but the ones I use most often. Pull requests are welcome.

I had wanted to line break this module for better viewing, but I'm currently having trouble figuring out how to get some of the code to work over multiple lines. I'll keep working at it and hopefully I'll have a more web-friendly version soon.

Instructions for Use:

  1. Copy the contents of this script to a file called Microsoft.DHCP.PowerShell.Admin.psm1.
  2. Load this module using the Import-Module cmdlet.
  3. Get a list of cmdlets using the Get-DHCPCommand cmdlet.
  4. Get a detailed explanation of each command using the Get-Help cmdlet. 

Note that seven new structures/data types are created by this module. To understand what attributes each structure has, see the Add-Type section at the top of the script.

## See Also

  * [Microsoft TechNet Posting][1]

## Author

Jeremy Engel

[1]:http://blogs.technet.com/b/heyscriptingguy/archive/2011/02/14/use-the-powershell-dhcp-module-to-simplify-dhcp-management.aspx

