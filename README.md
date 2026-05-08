# windows-troubleshooting-lab
# Windows Troubleshooting Lab – No Internet Connection

## Scenario
A Windows Server 2022 virtual machine lost internet connectivity after the Ethernet adapter was disabled.

## Symptoms
- Browser displayed “You’re not connected”
- Ping requests failed
- No active network connection detected

## Tools Used
- Command Prompt
- ipconfig
- ping
- Network Connections

## Troubleshooting Steps
1. Verified internet issue in browser.
2. Tested connectivity using:
   ```cmd
   ping 8.8.8.8
   ```
3. Investigated network configuration using:
   ```cmd
   ipconfig
   ```
4. Checked Network Connections settings.
5. Re-enabled the Ethernet adapter.
6. Verified successful connectivity using ping and browser test.

## Result
Internet connectivity restored successfully.


## Screenshots

### Browser Error


### Failed Ping
![Failed Ping](failed-ping.png)

### IP Configuration
![ipconfig](ipconfig.png)

### Successful Ping
![Successful Ping](successful-ping.png)
