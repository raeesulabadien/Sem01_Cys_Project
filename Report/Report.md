![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image1.png){width="0.9739588801399826in"
height="0.9166666666666666in"}

# Contents {#contents .TOC-Heading}

[***1. Topic Introduction***
[3](#topic-introduction)](#topic-introduction)

[**Objective:** [3](#_Toc185414181)](#_Toc185414181)

[**Content:** [3](#content)](#content)

[**Motivation:** [3](#_Toc185414183)](#_Toc185414183)

[***2. Description of Tool/Technique Used***
[3](#description-of-tooltechnique-used)](#description-of-tooltechnique-used)

[**Overview of Tool:** [3](#overview-of-tool)](#overview-of-tool)

[**Why Chosen:** [3](#_Toc185414186)](#_Toc185414186)

[**Example:** [3](#example)](#example)

[**Requirements:** [4](#requirements)](#requirements)

[**Hardware Requirements:**
[4](#hardware-requirements)](#hardware-requirements)

[**Software Specifications:**
[4](#software-specifications)](#software-specifications)

[**Networking Requirements:**
[4](#networking-requirements)](#networking-requirements)

[**Skill Requirements:** [4](#skill-requirements)](#skill-requirements)

[**Miscellaneous Requirements:**
[4](#miscellaneous-requirements)](#miscellaneous-requirements)

[***3. Progress*** [5](#progress)](#progress)

[***4. Demonstration of Attacking Techniques***
[6](#demonstration-of-attacking-techniques)](#demonstration-of-attacking-techniques)

[*4.1 & 4.2 Deauth Attack and Handshake Capture*
[6](#deauth-attack-and-handshake-capture)](#deauth-attack-and-handshake-capture)

[***Use case:*** [12](#use-case)](#use-case)

[5. Airgeddon Limitations
[14](#airgeddon-limitations)](#airgeddon-limitations)

[6. Mitigation (If Any) [14](#mitigation-if-any)](#mitigation-if-any)

[7. Conclusion [15](#conclusion)](#conclusion)

[Report on Airgeddon Project]{.underline}

# ***1. Topic Introduction***

[]{#_Toc185414181 .anchor}**Objective:** To explore the functionality
and applications of Airgeddon, a versatile tool designed for wireless
network auditing and penetration testing.

## **Content:** 

This project discusses Airgeddon to demonstrate its capability in
enhancing wireless network security. The increasing use of WiFi networks
in modern society has made them a prime target for cyberattacks. Tools
like Airgeddon are necessary to identify vulnerabilities and strengthen
networks.

[]{#_Toc185414183 .anchor}**Motivation:** The purpose of the project is
to understand the procedures of wireless auditing and deploy effective
measures in enhancing network security.

#  ***2. Description of Tool/Technique Used***

## **Overview of Tool:**

**Name:** Airgeddon

**Version:** Release 105 (version 11.40)

[]{#_Toc185414186 .anchor}**Why Chosen:** The reason for using Airgeddon
is that it can be adapted to perform such activities like wireless
network auditing, handshakes, and assessing network strength. This tool
comes with an intuitive interface, along with welldocumented
information, so it can be used effectively by anyone, from new to
experienced users.

**Important Features Utilized:**

1.  Wireless network discovery

2.  Deauthentication attacks

3.  Capture of WPA/WPA2 handshake

4.  Dictionary attack/Password Cracking

5.  Fake AP creation

## **Example:**

Airgeddon\'s enhanced wireless audits make it possible to simulate
realistic attack scenarios for users; this makes it possible for them to
improve their networks\' defenses. Below is a screenshot of the tool
while in action.

![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image2.png){width="6.30251312335958in"
height="1.67874343832021in"}

## **Requirements:**

Some Requirements to carry the attacks are as follows:

### **Hardware Requirements:** 

1\. **Wireless Network Adapter:**

An adapter capable of monitor mode and packet injection (e.g., Alfa
AWUS036NHA or TP-Link TL-WN722N).

**2. Secondary Wireless Interface (Optional):**

Only required for conducting dual-interface tasks like simultaneous
scanning and attacking.

**3. System:**

A desktop computer or laptop that possesses adequate processing
capabilities and a minimum of 4GB of RAM.

### **Software Specifications:** 

**1. OS:**

Kali Linux. As it already has a plethora of built-in utilities that are
set to use out of the box and, therefore compatible.

**2. Airgeddon:**

11.20 (Release 105) or latest

**3. Dependencies:**

Ensure that all the prerequisites to run Airgeddon are installed, such
as \`aircrack-ng\`, \`iwconfig\`, and \`mdk3\`.

### **Networking Requirements:** 

**1. Target Network:**

A test network specifically created for learning purposes. Before
conducting an audit on any network, ethical and legal permission is
required to be acquired.

### **Skill Requirements:** 

**1. Basic Linux knowledge**

Knowledge of the directives required for moving around and deploying
tools using a Linux platform.

**2. Wireless Networking:**

Understanding of Wi-Fi protocols, including WPA/WPA2 as well as its
vulnerabilities

**3. Ethics:**

Familiarization with ethical hacking principles or best practices, along
with local statutes to ensure safe use of tools.

### **Miscellaneous Requirements:** 

**1. External Antenna (Optional):**

To increase signal strength for weak networks.

**2. Power Supply:**

To provide constant power to carry out long operations.

# ***3. Progress***

**Objective:** Provide a chronological breakdown of the project
milestones.

  -----------------------------------------------------------------------
  Date                    Milestone               Description
  ----------------------- ----------------------- -----------------------
  Dec 16, 2024            Topic Selection         Chose the topic of
                                                  Airgeddon for the
                                                  project

  Dec 18, 2024            Sample Attack Conducted Performed an initial
                                                  sample attack to
                                                  understand tool
                                                  functionality.

  Dec 19, 2024            Issue Encountered       Identified a limitation
                                                  of having only one
                                                  wireless interface.

  Dec 20, 2024            Mitigation of Issue     Arranged an additional
                                                  wireless interface from
                                                  a friend to proceed
                                                  with the attacks.

  Dec 21, 2024            Final Attack and Report Conducted a full
                                                  attack, documented the
                                                  steps, and captured
                                                  relevant screenshots
                                                  for the report.
  -----------------------------------------------------------------------

**Details of Activities:**

1.  **Topic Selection:** The project topic, Airgeddon, was chosen on Dec
    16, 2024, due to its relevance to wireless security.

2.  **Sample Attack:** A sample attack was performed on Dec 18, 2024, to
    familiarize the team with the tool and its features. No major issues
    were encountered during this phase.

3.  **Hardware Limitation:** On Dec 19, 2024, we realized that having
    only one wireless interface was insufficient for simultaneous
    scanning and attacking. This issue was addressed by borrowing an
    additional interface from a friend on Dec 20, 2024.

4.  **Final Attack:** The final attack was performed on Dec 21, 2024,
    with both interfaces in use. Screenshots and detailed steps were
    recorded for documentation purposes.

# ***4. Demonstration of Attacking Techniques***

**Objective:**\
To demonstrate Airgeddon's ability to identify and exploit
vulnerabilities in a wireless network.

## ***4.1 & 4.2 Deauth Attack and Handshake Capture***

**Goal:**

Perform a deauthentication attack to disconnect clients from a wireless
network and capture the WPA/WPA2 handshake for further analysis.

**Objective:**

Conduct a deauthentication attack on the target network to briefly drop
devices from the targeted network and capture the handshake packet when
the devices try to reconnect to the attacked network as follows.

### ***Details of Deauth attack:***

1.  First start the airgeddon tool:

> ![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image3.png){width="3.3890627734033245in"
> height="1.4097944006999126in"}

The following screen will appear and now the tool will check for
necessary required sub tools:

![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image4.png){width="6.031830708661417in"
height="3.1686417322834646in"}

2.  Now the tool/script will ask you to select an interface to conduct
    the attack.

> ![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image5.png){width="6.042165354330709in"
> height="1.554705818022747in"}
>
> **Note: if you are using kali virtual machine you will get the first
> interface as eth0(Do not select this one) and also you need to have
> two external wireless adapters to carry out a proper attack.**

3.  Select one of the two wireless interface. We have selected the 2^nd^
    one.

> ![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image6.png){width="6.149815179352581in"
> height="0.6487095363079615in"}

4.  You will get the following interface:

> ![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image7.png){width="6.170710848643919in"
> height="2.7893788276465443in"}

5.  First you need to put your network interface into monitoring mode to
    do that enter 2:

> ![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image8.png){width="6.257302055993001in"
> height="1.5032556867891513in"}

Press enter and you will be back to this interface:

![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image9.png){width="6.4636832895888015in"
height="3.3022462817147855in"}

**Note: But see on the top most of the terminal you will see that now
your network interface is in monitoring mode (You are all set to go).**

6.  Now focus on the options from (4 - 10). You will see
    Handshake/PMKID/Deloaking tools menu. Press to enter in the menu.

> ![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image10.png){width="6.449094488188976in"
> height="2.871467629046369in"}

7.  We are interested in the capture of handshake file so we will press
    6 to start the attack.

> ![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image11.png){width="6.536411854768154in"
> height="1.1786964129483815in"}
>
> There is no target network selected. Press enter and you will see a
> magic.
>
> ![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image12.png){width="6.57334864391951in"
> height="1.0017672790901138in"}
>
> Press enter to scan targets near you and wait for 30 seconds and then
> press Ctrl + C to stop scanning.
>
> You will get the following interface:
>
> ![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image13.png){width="6.487274715660543in"
> height="2.10250656167979in"}
>
> **Note: The \* sign indicates the targets with clients connected.**

8.  Now select the target network in our case we will select **NTL
    Ground Floor** as we have the permission to attack this network
    (Never attack the network you don't have permission to) You will get
    the following options.

> ![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image14.png){width="6.52538823272091in"
> height="1.573675634295713in"}

**Note:**

**a. Deauth / disassoc amok mdk4 attack:** This is a method used to
disrupt the connection between a device and a wireless access point
(AP). The \"deauth\" (de-authentication) and \"disassoc\"
(disassociation) attacks send spoofed packets to disconnect users from
the Wi-Fi network. The term \"mdk4\" refers to a tool that allows
multiple types of wireless attacks, including this one.

**b. Deauth airplay attack:** Similar to the above, this attack
specifically targets the Wi-Fi devices using a method to forcefully
disconnect them from the network. \"Airplay\" is often associated with
frameworks used in Wi-Fi testing, targeting devices that are
communicating over the air to induce reconnection attempts or to capture
handshake data.

**c. Auth DoS attack:** An authentication denial-of-service (Auth DoS)
attack aims to overwhelm a network with authentication requests, causing
legitimate devices to be unable to connect. This attack exploits the way
WPA/WPA2 authentication works and can be used to disrupt the
availability of the network.

9.  In our case we will be going with the 2^nd^ method to deauth the
    clients connected to the network.

> ![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image15.png){width="6.497327209098863in"
> height="0.5307863079615048in"}
>
> The tool is asking you to select a time interval in which after it
> sends the deauth packets until a handshake file is captured. We will
> go with the default timer.
>
> ![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image16.png){width="6.587229877515311in"
> height="0.7804472878390202in"}
>
> Press enter to the start the attack.
>
> ![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image17.png){width="1.4584087926509186in"
> height="0.7222594050743657in"}
>
> As you can see two external windows are doing the work for you.

10. Now if the attack is successful you will be prompted to enter a path
    where to store the captured handshake file.

> ![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image18.png){width="6.6972320647419075in"
> height="0.7102930883639546in"}

In our case we will give the Desktop for our convenience.

![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image19.png){width="6.5959437882764655in"
height="0.8627788713910761in"}

To confirm that our file is stored in the specific directory.

![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image20.png){width="6.45920384951881in"
height="0.9217771216097987in"}

11. Focusing on our tool now you will get the following interface

> ![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image21.png){width="6.348451443569553in"
> height="3.4186767279090113in"}
>
> But just focus on the top of the terminal, you will get the details
> about our target network. But for now we will go back to our main
> menu.

12. Handshake file details (We thought it will be better to add this)

> ![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image22.png){width="6.445636482939633in"
> height="3.2462204724409447in"}
>
> As you can see we have the WPA key in encrypted form and that's all
> for this attack. Further information on how to decrypt this key or
> match the hash of the key is in the next sections.

### **Methodology:**

•A wireless adapter is used in monitor mode to carry out the attack

•Handshake packets are saved in a cap file for further analysis such as
password cracking

### ***Use case:***

This method illustrates how attackers can use the weaknesses of the
network to steal encrypted authentication data. The configurations must
be secure.

## ***4.3 Dictionary Attack***

-   **Objective:** Crack the WPA/WPA2 password using the captured
    handshake.

### **Methodology:**

1.  Load the handshake file into password-cracking (Provided with
    Airgeddon)

2.  Attempt password guessing using a dictionary or brute force
    technique.

### ***Details of Dictionary/Brute Force Attack:***

1.  Coming back to the main menu:

> ![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image23.png){width="6.301349518810149in"
> height="1.9976946631671042in"}

2.  Select the **[6. Offline WPA/WPA2 decrypt menu]{.underline}**
    option.

> ![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image24.png){width="6.417783245844269in"
> height="2.7342727471566053in"}
>
> Focus on the top of the terminal where the information is given about
> the decrypt methods and the selected handshake file. Select the option
> depending on the network you attacked (if it was enterprise select
> 2^nd^ option and if it is simple select the 1^st^ option). In our case
> we have selected 1^st^ option.

3.  You will be treated with the following menu:

> ![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image25.png){width="6.6360269028871395in"
> height="2.2306080489938758in"}
>
> **Note: There are lots of offline attacks you can perform using
> airgeddon. In this report we are covering "[(aircrack) Dictionary
> attack against Handshake/PMKID capture file]{.underline}" attack**

4.  Carrying the attack:

> ![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image26.png){width="6.692053805774278in"
> height="0.906081583552056in"}
>
> The tool will ask you to select a handshake file but if you have
> already selected a target network and captured a handshake file, the
> tool will automatically select the captured file.
>
> ![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image27.png){width="6.650226377952756in"
> height="1.0312751531058617in"}
>
> Press Y to continue

5.  Now you will get a prompt to enter the path for a file that contains
    password for dictionary attack (You can find one on the internet
    that contains compromised passwords). In my case I have a file
    stored on the Desktop.

> ![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image28.png){width="4.534955161854768in"
> height="1.0417202537182852in"}

6.  Press enter to start the attack.

> ![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image29.png){width="6.649480533683289in"
> height="3.58244750656168in"}
>
> **Note: The dictionary attack will only be successful if your target
> network has a compromised password like "12345678" or "0000000" and
> like that.**

### ***Use case:***

A dictionary attack is used to crack WPA/WPA2 passwords by
systematically testing a list of pre-defined potential passwords against
the captured handshake to find the correct one.

## ***4.4 Evil Twin Attack***

-   **Objective:** Create a fake access point to trick users into
    sharing their Wi-Fi password.

### **Methodology:**

1.  Configure Airgeddon to create a fake AP.

2.  Broadcast the rogue AP and monitor connections.

3.  Collect authentication details entered by unsuspecting users.

*Note: Parrot OS is used for this attack because it's better at this
attack and does not get interrupted*

*Since we have already conducted multiple attacks and understood the
interface we will just move to main points of this attack.*

*Details of Evil Twin Attack:*

1.  Return to main menu and select Evil twin Attack

![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image30.jpg){width="6.284583333333333in"
height="1.992361111111111in"}

2.  Start evil twin attack with captive portal at the end

![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image31.png){width="6.798611111111111in"
height="3.8222222222222224in"}

3.  Search and choose the network as before

![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image32.png){width="7.268055555555556in"
height="3.810416666666667in"}

4.  Use the Deauth and Disassoc attack

![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image33.png){width="7.268055555555556in"
height="2.276388888888889in"}

5.  Use recently used handshake

![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image34.png){width="7.268055555555556in"
height="2.59375in"}

6.  Choose the language and start attack

![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image35.png){width="7.268055555555556in"
height="3.410416666666667in"}

7.  Attack Screen

> ![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image36.png){width="6.777777777777778in"
> height="3.729861111111111in"}

8.  User's End Screen

![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image37.jpeg){width="4.788194444444445in"
height="5.722222222222222in"}

9.  Password will be stored at given Location

![](vertopal_1491b1cfa0c242f4ba5455d4c3d35779/media/image38.png){width="7.268055555555556in"
height="3.45625in"}

### 5. Airgeddon Limitations

**Known Issues:**

1.  **Hardware Dependency:** Requires compatible wireless adapters for
    optimal performance.

2.  **Ethical Considerations:** Improper use could lead to legal
    consequences.

3.  **Manual Intervention:** Some tasks lack automation, increasing the
    complexity for beginners.

4.  **Detection Risks:** Intrusion detection systems (IDS) can identify
    activities like deauthentication attacks.

### 6. Mitigation (If Any)

**Challenge:**\
Some networks were not detected during the discovery phase due to low
signal strength.

**Mitigation:**

-   Used an external antenna to boost signal reception.

-   Optimized Airgeddon's settings for better range detection.

\[Insert Screenshot of Successful Mitigation\]

### 7. Conclusion

**Summary:**\
The project successfully utilized Airgeddon for wireless auditing. Key
objectives, such as handshake capturing and vulnerability
identification, were achieved.

**Future Work:**\
Future analysis could explore additional modules of Airgeddon, such as
Evil Twin attacks, or incorporate other tools for comprehensive
penetration testing.

**Personal Takeaway:**\
This project highlighted the practical applications of cybersecurity
tools and reinforced concepts related to wireless network
vulnerabilities.

**Extra Notes:**\
Ensure compliance with legal and ethical guidelines. Replace
placeholders with actual screenshots and data.
