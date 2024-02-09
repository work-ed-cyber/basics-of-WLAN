<h1> Lesson 6.2: Basics of WLANs</h1>
<h2> Summary</h2>

<p1>This lesson introduces students to the foundational concepts of Wireless Local Area Networks (WLANs). By understanding WLANs' structure, functioning, and security, students will be better equipped to safely and efficiently utilize wireless networks.</p1>
<br>

<h2>Learning Objectives</h2>
<ul>
<li>Students will be able to explain what a WLAN is, how it functions, and its main components.</li>
  <br>
<li>Students will identify the standard frequency bands used in WLANs and discuss their significance.</li><br>

<li>Students will describe standard security measures, including WPA/WPA2/WPA3, and the importance of securing wireless networks.</li><br>
  
<li>By the end of the lesson, students should be able to set up a simple WLAN, assign an SSID, and apply basic security settings.</li><br>
<li>Students will analyze real-world scenarios to determine the best practices for setting up and securing WLANs in various environments.</li>

</ul>

<h2>Vocabulary and Acronyms</h2>

<ul>
  <li>

**WLAN**</li>
  
<li>
  
**WPA/WPA2/WPA3**</li>

<li>

**Hotspot**</li>
  
<li>
  
**AP - Access Point**</li>

<li>
  
**Frequency Bands**</li>

<li>
  
**MAC Address Filtering**</li>

<li>
  
**SSID**</li>

<li>
  
**Channel**</li>


</ul>

<h2>NICE Framework KSAs</h2>
<ul>
<li>K0113 - Knowledge of different types of network communication (e.g., LAN, WAN, MAN, WLAN, WWAN).</li>
<br>
<li>K0428 - Knowledge of encryption algorithms and tools for wireless local area networks (WLANs).</li>
<br>
<li>K0442	- Knowledge of how converged technologies impact cyber operations (e.g., digital, telephony, wireless).</li>
<br>
<li>K0446 - Knowledge of how modern wireless communications systems impact cyber operations.</li>
<br>
<li>K0600 - Knowledge of modern wireless communications systems' structure, architecture, and design.</li>
<br>
<li>S0182 - Skill in analyzing target communications internals and externals collected from wireless LANs.</li>
<br>
<li>S0276 - Skill in survey, collection, and analysis of wireless LAN metadata.</li>
<br>
<li>S0299 - Skill in wireless network target analysis, templating, and geolocation.</li> 
<br>
<li>A0100 - Ability to perform wireless collection procedures to include decryption capabilities/tools.</li>
</ul>


<h2>Lesson Prerequisites</h2>
<p1>Any topical or subject matter to prepare for the lesson. In Advanced Cyber Lessons, previous Lessons can be referenced. </p1>
<br>


<h2>Introduction</h2>
Wireless Local Area Networks, commonly called WLANs, have revolutionized how we access and share information. They facilitate establishing networks without the constraints of cables or fixed connections. In a world driven by connectivity, understanding WLANs is essential.


<h2>Definition and Key Concepts</h2>
A WLAN allows devices to connect and communicate wirelessly within a local area, such as a home, office, or school. The network is facilitated by devices called Access Points (APs), which serve as the central hub for the network.

<h3>Real-World Examples:</h3>

<ul>
<li><h4><ins>Home Networks</ins></h4></li>
	<ul><li>Most modern households have a WLAN, allowing family members to connect smartphones, laptops, smart TVs, and other devices to the internet wirelessly. The network name (SSID) might be something familiar, like "SmithFamilyWiFi," it would likely be secured using WPA2 or WPA3 to prevent unauthorized access.</li></ul>
 <li><h4><ins>Coffee Shops & Restaurants</ins></h4></li>
	<ul><li>Establishments often offer free Wi-Fi as an incentive for customers. You might have connected to an SSID like "CafeLatteFreeWiFi" while sipping your coffee. These networks, being public, have unique security challenges.</li></ul>
 <li><h4><ins>Educational Institutions</ins></h4></li>
	<ul><li>Schools and universities set up extensive WLANs to allow students and staff to access resources. Such networks might employ advanced features like MAC Address Filtering to ensure that only school-issued devices can connect.</li></ul>
 <li><h4><ins>Airports and Transport Hubs</h4></li>
 <ul><li> Airports often have WLANs named after the airport or the service provider. Given the high footfall, these WLANs are designed to handle many connections simultaneously.
</li></ul>
	
		
</ul>


<h2>Importance of WLAN Security</h2>

WLANs, especially public ones, are susceptible to various threats. Unauthorized access, data interception, and network misuse are just concerns. Therefore, implementing security measures, such as WPA3 encryption and MAC Address Filtering, is crucial.

For instance, a hacker might try to create a rogue hotspot at an airport with a similar SSID like "AirportFreeWiFi_2." Unsuspecting users might connect to this rogue network, exposing their data to the hacker. Thus, always ensuring connection to legitimate networks and employing personal security measures like VPNs becomes essential.


<h2>How Organizations Utilize WLANs</h2>

Wireless Local Area Networks (WLANs) are pivotal in today's digital environment. Beyond the usual convenience offered to individual users, organizations across industries are realizing the benefits of WLANs to optimize operations and enhance productivity.


<ul>
<li><h4><ins>Mobility and Flexibility</ins></h4></li>
	<ul><li>WLANs allow employees to move around the office environment – from conference rooms to individual workstations – without losing network connectivity. This promotes collaboration and real-time decision-making.</li></ul>
 <li><h4><ins>Guest Access</ins></h4></li>
	<ul><li>Companies often host clients, partners, or temporary workers. WLANs facilitate temporary guest access, ensuring connectivity without compromising security.
Operational Optimization: Some businesses, such as retailers or logistics firms, have integrated wireless LAN terminals to streamline operations. This allows for real-time inventory checks, order processing, and other crucial operations without being tethered to a particular location
</li></ul>
 <li><h4><ins>Cost-Efficiency</ins></h4></li>
	<ul><li>A WLAN can be more cost-effective than a wired network, especially in rented spaces or historical buildings where extensive cabling can be problematic.</li></ul>
 <li><h4><ins>Connectivity in Challenging Locations</h4></li>
	<ul><li>Areas where it's challenging to lay down wired networks, such as outdoor work environments or sprawling factory floors, can be networked using WLANs.</li></ul>
 <li><h4><ins>Fast Deployment</ins></h4></li>
 <ul><li>WLANs can be rapidly deployed, making them especially valuable for temporary setups, like events, pop-up stores, or emergency response centers.</li></ul>

</ul>

<h2>Challenges and Considerations</h2>

<ul>
	<li><h4><ins>Security</ins></h4></li>
	<ul>
		<li>Given the wireless nature, WLANs are vulnerable to security breaches. Organizations need robust security protocols to protect sensitive data. Regular audits and employing encryption protocols like WPA3 are essential.
		</li>
	</ul>
	<li><h4><ins>Interference</ins></h4></li>
	<ul>
		<li>Given that WLANs often operate in crowded frequency bands, interference from other devices can be an issue. Proper planning and network design can mitigate these challenges.
		</li>
	</ul>
	<li><h4><ins>Scalability</ins></h4></li>
	<ul>
		<li> As the organization grows, the WLAN must be scalable to accommodate more users and devices.

</li>
	</ul>
</ul>


<h2>Conclusion</h2>
WLANs offer many advantages to organizations, from enhanced flexibility to cost savings. While there are challenges to consider, particularly around security, with the right approach and ongoing management, the benefits can significantly outweigh the drawbacks. Wireless Local Area Networks have become integral to our daily lives, offering unparalleled convenience. As we navigate the digital world, understanding the basics of WLANs and their security implications is essential to ensure safe and efficient connectivity.

<h2> Presentation</h2>



<h2> Hands-On Labs</h2>


<h2> Additional Resources</h2>


