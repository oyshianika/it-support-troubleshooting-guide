# IT Support Troubleshooting Guide

A practical collection of common IT support issues and their step-by-step fixes, based on hands-on troubleshooting experience and the Google IT Support Professional Certificate.

## Windows Issues

### Computer running slow
1. Check Task Manager for high CPU/memory usage processes
2. Disable unnecessary startup programs
3. Run Disk Cleanup and check available storage space
4. Check for pending Windows updates
5. Scan for malware using Windows Defender

### Computer won't boot
1. Check power cable and connections
2. Try a hard restart (hold power button 10 seconds)
3. Boot into Safe Mode to check for driver/software conflicts
4. Check for recent hardware or software changes
5. Run Startup Repair from Windows Recovery

### Blue Screen of Death (BSOD)
1. Note the error code shown on screen
2. Check for recently installed drivers or hardware
3. Run Windows Memory Diagnostic
4. Update or roll back device drivers
5. Check Event Viewer for detailed error logs

## Network Issues

### No internet connection
1. Check physical cable/Wi-Fi connection
2. Restart router/modem
3. Run `ipconfig /release` then `ipconfig /renew` (Command Prompt)
4. Flush DNS: `ipconfig /flushdns`
5. Check if the issue is device-specific or network-wide

### Slow internet / intermittent connection
1. Test speed on multiple devices to isolate the issue
2. Check for interference (distance from router, other devices)
3. Update network adapter drivers
4. Check for bandwidth-heavy background applications
5. Contact ISP if issue persists across all devices

## Account & Access Issues

### Forgotten password / locked account
1. Verify user identity following company policy
2. Use self-service password reset if available
3. Reset password via Active Directory (admin access)
4. Check for account lockout policies (failed attempt limits)
5. Ensure MFA is set up correctly after reset

### Permission / access denied errors
1. Confirm user's role and required access level
2. Check group membership in Active Directory
3. Verify file/folder sharing permissions
4. Check if account is disabled or expired
5. Escalate to appropriate access owner if needed

## Hardware Issues

### Printer not working
1. Check printer power and cable/network connection
2. Verify printer is set as default device
3. Clear print queue and restart print spooler service
4. Reinstall or update printer drivers
5. Check for paper jams or low ink/toner

### Monitor / display issues
1. Check cable connections (HDMI/VGA/DisplayPort)
2. Test with a different cable or port
3. Update graphics drivers
4. Check display settings (resolution, refresh rate)
5. Test monitor on another device to isolate the fault

## General Troubleshooting Approach

1. **Identify** – Gather information about the issue from the user
2. **Reproduce** – Try to recreate the issue if possible
3. **Isolate** – Narrow down whether it's hardware, software, or network
4. **Resolve** – Apply the appropriate fix, starting with the simplest solution
5. **Document** – Record the issue and resolution for future reference
6. **Follow up** – Confirm with the user that the issue is fully resolved

---
*Compiled from hands-on IT support experience and Google IT Support Professional Certificate coursework.*
