---
title: Policy CSP - Wifi
description: Policy CSP - Wifi
ms.author: maricia
ms.topic: article
ms.prod: w10
ms.technology: windows
author: nickbrower
ms.date: 07/14/2017
---

# Policy CSP - Wifi

> [!WARNING]
> Some information relates to prereleased product which may be substantially modified before it's commercially released. Microsoft makes no warranties, express or implied, with respect to the information provided here.

<!--StartPolicies-->
<hr/>

## Wifi policies  

<!--StartPolicy-->
<a href="" id="wifi-allowwifihotspotreporting"></a>**WiFi/AllowWiFiHotSpotReporting**  

<!--StartSKU-->

<!--EndSKU-->
<!--StartDescription-->
<p style="margin-left: 20px">This policy has been deprecated.

<!--EndDescription-->
<!--EndPolicy-->
<!--StartPolicy-->
<a href="" id="wifi-allowautoconnecttowifisensehotspots"></a>**Wifi/AllowAutoConnectToWiFiSenseHotspots**  

<!--StartSKU-->
<table>
<tr>
	<th>Home</th>
	<th>Pro</th>
	<th>Business</th>
	<th>Enterprise</th>
	<th>Education</th>
	<th>Mobile</th>
	<th>Mobile Enterprise</th>
</tr>
<tr>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
</tr>
</table>

<!--EndSKU-->
<!--StartDescription-->
<p style="margin-left: 20px">Allow or disallow the device to automatically connect to Wi-Fi hotspots.

<p style="margin-left: 20px">The following list shows the supported values:

-   0 – Not allowed.
-   1 (default) – Allowed.

<p style="margin-left: 20px">Most restricted value is 0.

<!--EndDescription-->
<!--EndPolicy-->
<!--StartPolicy-->
<a href="" id="wifi-allowinternetsharing"></a>**Wifi/AllowInternetSharing**  

<!--StartSKU-->
<table>
<tr>
	<th>Home</th>
	<th>Pro</th>
	<th>Business</th>
	<th>Enterprise</th>
	<th>Education</th>
	<th>Mobile</th>
	<th>Mobile Enterprise</th>
</tr>
<tr>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
</tr>
</table>

<!--EndSKU-->
<!--StartDescription-->
<p style="margin-left: 20px">Allow or disallow internet sharing.

<p style="margin-left: 20px">The following list shows the supported values:

-   0 – Do not allow the use of Internet Sharing.
-   1 (default) – Allow the use of Internet Sharing.

<p style="margin-left: 20px">Most restricted value is 0.

<!--EndDescription-->
<!--EndPolicy-->
<!--StartPolicy-->
<a href="" id="wifi-allowmanualwificonfiguration"></a>**Wifi/AllowManualWiFiConfiguration**  

<!--StartSKU-->
<table>
<tr>
	<th>Home</th>
	<th>Pro</th>
	<th>Business</th>
	<th>Enterprise</th>
	<th>Education</th>
	<th>Mobile</th>
	<th>Mobile Enterprise</th>
</tr>
<tr>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>1</sup></td>
	<td></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>1</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>1</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
</tr>
</table>

<!--EndSKU-->
<!--StartDescription-->
<p style="margin-left: 20px">Allow or disallow connecting to Wi-Fi outside of MDM server-installed networks.

<p style="margin-left: 20px">The following list shows the supported values:

-   0 – No Wi-Fi connection outside of MDM provisioned network is allowed.
-   1 (default) – Adding new network SSIDs beyond the already MDM provisioned ones is allowed.

<p style="margin-left: 20px">Most restricted value is 0.

> [!NOTE]
> Setting this policy deletes any previously installed user-configured and Wi-Fi sense Wi-Fi profiles from the device. Certain Wi-Fi profiles that are not user configured nor Wi-Fi sense might not be deleted. In addition, not all non-MDM profiles are completely deleted.

<!--EndDescription-->
<!--EndPolicy-->
<!--StartPolicy-->
<a href="" id="wifi-allowwifi"></a>**Wifi/AllowWiFi**  

<!--StartSKU-->
<table>
<tr>
	<th>Home</th>
	<th>Pro</th>
	<th>Business</th>
	<th>Enterprise</th>
	<th>Education</th>
	<th>Mobile</th>
	<th>Mobile Enterprise</th>
</tr>
<tr>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>1</sup></td>
	<td></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>1</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>1</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
</tr>
</table>

<!--EndSKU-->
<!--StartDescription-->
<p style="margin-left: 20px">Allow or disallow WiFi connection.

<p style="margin-left: 20px">The following list shows the supported values:

-   0 – WiFi connection is not allowed.
-   1 (default) – WiFi connection is allowed.

<p style="margin-left: 20px">Most restricted value is 0.

<!--EndDescription-->
<!--EndPolicy-->
<!--StartPolicy-->
<a href="" id="wifi-allowwifidirect"></a>**Wifi/AllowWiFiDirect**  

<!--StartSKU-->
<table>
<tr>
	<th>Home</th>
	<th>Pro</th>
	<th>Business</th>
	<th>Enterprise</th>
	<th>Education</th>
	<th>Mobile</th>
	<th>Mobile Enterprise</th>
</tr>
<tr>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>2</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>2</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>2</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>2</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>2</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>2</sup></td>
</tr>
</table>

<!--EndSKU-->
<!--StartDescription-->
<p style="margin-left: 20px">Added in Windows 10, version 1703. Allow WiFi Direct connection..

- 0 - WiFi Direct connection is not allowed.
- 1 - WiFi Direct connection is allowed.

<!--EndDescription-->
<!--EndPolicy-->
<!--StartPolicy-->
<a href="" id="wifi-wlanscanmode"></a>**Wifi/WLANScanMode**  

<!--StartSKU-->
<table>
<tr>
	<th>Home</th>
	<th>Pro</th>
	<th>Business</th>
	<th>Enterprise</th>
	<th>Education</th>
	<th>Mobile</th>
	<th>Mobile Enterprise</th>
</tr>
<tr>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
</tr>
</table>

<!--EndSKU-->
<!--StartDescription-->
<p style="margin-left: 20px">Allow an enterprise to control the WLAN scanning behavior and how aggressively devices should be actively scanning for Wi-Fi networks to get devices connected.

<p style="margin-left: 20px">Supported values are 0-500, where 100 = normal scan frequency and 500 = low scan frequency.

<p style="margin-left: 20px">The default value is 0.

<p style="margin-left: 20px">Supported operations are Add, Delete, Get, and Replace.

<!--EndDescription-->
<!--EndPolicy-->
<hr/>

Footnote:

-   1 - Added in Windows 10, version 1607.
-   2 - Added in Windows 10, version 1703.
-   3 - Added in Windows 10, version 1709.

<!--EndPolicies-->

<!--StartEAS-->
## <a href="" id="eas"></a>Wifi policies that can be set using Exchange Active Sync (EAS)  

-   [Wifi/AllowInternetSharing](#wifi-allowinternetsharing)  
-   [Wifi/AllowWiFi](#wifi-allowwifi)  
<!--EndEAS-->

<!--StartIoTCore-->
## <a href="" id="iotcore"></a>Wifi policies supported by IoT Core  

-   [Wifi/AllowAutoConnectToWiFiSenseHotspots](#wifi-allowautoconnecttowifisensehotspots)  
-   [Wifi/AllowInternetSharing](#wifi-allowinternetsharing)  
-   [Wifi/AllowWiFi](#wifi-allowwifi)  
-   [Wifi/WLANScanMode](#wifi-wlanscanmode)  
<!--EndIoTCore-->

<!--StartSurfaceHub-->
 
<!--EndSurfaceHub-->

