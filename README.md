Single-Host Static IPv4 Addressing & Local Loopback Verification

📌 Project Overview

This project demonstrates the configuration and verification of a standalone workstation using Cisco Packet Tracer.

PC0 is configured with a static IPv4 address, subnet mask, default gateway, and DNS server. The configuration is verified using Command Prompt utilities.

 🎯 Objective

The objectives of this project are:

- To configure static IPv4 addressing.
- To verify network parameters using `ipconfig /all`.
- To test the local TCP/IP protocol stack using `ping 127.0.0.1`.
- To verify the assigned IP address using `ping 192.168.10.25`.

 💻 Software Requirements

- Cisco Packet Tracer
- PC0 workstation
- Desktop IP Configuration
- Command Prompt

 ⚙️ Network Configuration Details

| Parameter       | Value         |
| --------------- | ------------- |
| Device Name     | PC0           |
| IPv4 Address    | 192.168.10.25 |
| Subnet Mask     | 255.255.255.0 |
| Default Gateway | 192.168.10.1  |
| DNS Server      | 8.8.8.8       |

 📖 Theory

Static IPv4 addressing assigns a fixed IP address to a workstation. The subnet mask identifies the network portion, the default gateway forwards traffic to other networks, and DNS translates domain names into IP addresses.

The loopback address `127.0.0.1` is used to test the local TCP/IP protocol stack.

 📝 Procedure
Step 1: Launch Cisco Packet Tracer
1. Open the Cisco Packet Tracer application on the computer.
2. Wait until the main workspace appears.
3. Select the **Logical Workspace** to create the network setup.


 Step 2: Add the PC Device
1. Locate the device selection panel at the bottom-left corner.
2. Click **End Devices**.
3. Select a generic PC from the available devices.
4. Drag and drop the PC into the workspace.
5. Ensure that the device name is displayed as **PC0**.

 Step 3: Configure Static IPv4 Addressing
1. Click on **PC0** to open its device window.
2. Navigate to the **Desktop** tab.
3. Select **IP Configuration**.
4. Choose the **Static** option to assign the IP address manually.
5. Enter the following network parameters:

   - IPv4 Address: `192.168.10.25`
   - Subnet Mask: `255.255.255.0`
   - Default Gateway: `192.168.10.1`
   - DNS Server: `8.8.8.8`

6. Verify that all values have been entered correctly.
7. Close the IP Configuration window.

 Step 4: Open Command Prompt
1. Click on PC0 again if the device window is closed.
2. Select the **Desktop** tab.
3. Click **Command Prompt**.
4. Wait for the command-line interface to appear.

 Step 5: Verify IP Configuration
1. Type the following command in Command Prompt:

   `ipconfig /all`

2. Press **Enter**.
3. Observe the network configuration displayed on the screen.
4. Verify that the IPv4 address is `192.168.10.25`.
5. Confirm that the subnet mask is `255.255.255.0`.
6. Check that the default gateway and DNS server match the configured values.

 Step 6: Test the Local TCP/IP Protocol Stack
1. In Command Prompt, type:

   `ping 127.0.0.1`

2. Press **Enter**.
3. Observe the replies returned by the loopback address.
4. Check whether the ping test completes successfully with zero packet loss.
5. Record the output for verification.

 Step 7: Verify the Assigned IPv4 Address
1. Type the following command:

   `ping 192.168.10.25`

2. Press **Enter**.
3. Observe the response from the workstation's assigned IP address.
4. Confirm that successful replies are received.
5. Verify that the packet loss is 0%.
6. Record the result of the test.

 Step 8: Analyze the Results
1. Compare the displayed IP configuration with the assigned values.
2. Check the loopback ping result to verify local TCP/IP functionality.
3. Check the assigned-IP ping result to verify that the workstation responds at its configured address.
4. Record any errors or packet loss if they occur.
5. Conclude whether the specified configuration and verification tests were successful.
6. <img width="1254" height="1254" alt="image" src="https://github.com/user-attachments/assets/23b7f881-5a7c-4086-9d30-627ddfef1ef6" />
<img width="653" height="546" alt="image" src="https://github.com/user-attachments/assets/81d785ea-6a05-4211-b6b0-61cd207d018b" />


🖥️ Commands and Expected Results

Command 1:

`ipconfig /all`

Expected result: The configured IPv4 address and subnet mask should be displayed correctly.

Command 2:

`ping 127.0.0.1`

Expected result: Successful loopback replies with zero packet loss.

Command 3:

`ping 192.168.10.25`

Expected result: Successful replies from the assigned IP address with zero packet loss.
<img width="1386" height="1135" alt="image" src="https://github.com/user-attachments/assets/fd55d385-334c-4f6f-8b15-d4d4e3b028ea" />


 📊 Observation

| Test             | Expected Outcome   |
| ---------------- | ------------------ |
| IP configuration | Correct parameters |
| Loopback ping    | Successful         |
| Assigned IP ping | Successful         |
| Packet loss      | 0%                 |

 🔍 Result Analysis

The `ipconfig /all` command checks the configured network parameters. The loopback test verifies local TCP/IP functionality, while the assigned-IP test checks whether PC0 responds at its configured address.

 🚀 Innovative Applications

This verification method is useful for basic workstation setup, computer laboratory maintenance, network administration training, and troubleshooting IP configuration errors.

 ⚠️ Precautions

- Enter all IP parameters correctly.
- Check the subnet mask carefully.
- Run each command without spelling errors.
- Record the actual output displayed in Packet Tracer.
- Remember that a local ping does not prove external network connectivity.

 ✅ Conclusion

Thus, PC0 was configured with static IPv4 parameters in Cisco Packet Tracer. The `ipconfig /all` and ping commands were used to verify the configuration and local TCP/IP functionality. Successful responses with zero packet loss indicate that the specified local verification tests have passed.

 👩‍💻 Author

**Krishnaveni**

**Course:** B.Tech – Computer Science and Business Systems

---

 ⭐ Project Status

**Completed**
