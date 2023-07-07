# use Cisco Anyconnect client max version 4.9
Support for Windows 7 is discontinued from version 4.10
Cisco Anyconnect client version 4.9 installer can be found in [this repo](https://github.com/hbghlyj/openconnect-sso/blob/Qt5/anyconnect-win-4.9.01095-core-vpn-predeploy-k9.msi)
Note: All old version installers are removed from official website.
# use Qt 5
Since Qt 6 doesn't support  Windows 7, you will run into problems with the latest version of `openconnect-sso`.
# Wintun driver installation
The driver is not automatically installed, so you need to install it separately:
1. Download OpenVPN GUI from http://staging.openvpn.net/openvpn2/ or [this repo](https://github.com/hbghlyj/openconnect-sso/blob/Qt5/openvpn-install-2.5_git_wintun-I607-Win7.exe)
2. When you install it, check only the Wintun driver installation. Screenshot:
   
   ![捕获](https://github.com/hbghlyj/openconnect-sso/assets/53823634/f71f1871-5c7e-4690-85dd-33dbca32f0d3)
   
   Confirm to trust installer:
   
   ![捕获](https://github.com/hbghlyj/openconnect-sso/assets/53823634/bf10ca66-cdce-4d5d-b81e-499ac18c78ee)
4. If Wintun driver is successfully installed, you can see "Wintun userspace tunnel" under "network adapter" in [device manager](https://support.microsoft.com/en-us/windows/open-device-manager-a7f2db46-faaf-24f0-8b7b-9e4a6032fc8c).
   
   ![捕获](https://github.com/hbghlyj/openconnect-sso/assets/53823634/1f59a47c-f1e7-47d9-a23a-0cbcf443e76c)
