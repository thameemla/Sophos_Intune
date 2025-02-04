# Sophos_Intune
The process and code to integrate your Sophos with Intune
Created by LJ **This is the script used for to Install Sophos Zero Touch via Intune. ** First create a config profile in Intune through navigating to Devices -> MacOS -> Configuration Profiles -> create -> New Policy Choose Profile Type Custom -> then add the configuraton Profile. Proceed Next steps assign scope and save.

Now download the Sophos Installer from your Sophos Instance as zip. click get Info and get the URL from where from replace the url in the quote section in the script. Save the file.

Now in Intune Devices -> MacOS -> Shell scripts -> Add -> choose the file Proceed Next steps assign scope and save.
