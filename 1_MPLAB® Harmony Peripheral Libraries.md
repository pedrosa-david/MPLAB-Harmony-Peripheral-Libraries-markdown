[↑ Up to Section](main.md)

[↑↑ Back to Main Documentation](main.md)

# 1
MPLAB® Harmony Peripheral Libraries

_Generated on: 2025-02-19 08:42:41_

_Source: https://onlinedocs.microchip.com/oxy/GUID-450989FA-38E4-4D68-AB61-15ADB29AD718-en-US-5/GUID-AF6BCA35-9CEB-4457-AEC4-64AE5B7C0745.html_

# 1 MPLAB® Harmony Peripheral Libraries

MPLAB® Harmony Chip Support Package (CSP) supports configuration of Microchip 32-bit microcontroller and microprocessor devices.  This support can be used to initialize basic functionality necessary in order to use the device.  When using the MCC to only generate minimal device configuration code, the application developer must create all additional logic.  This includes any further peripheral control logic and potentially complex middleware

In addition to minimal device initialization, many developers prefer simple and direct control over peripherals with minimal overhead.  To support this model, a developer can use the MCC to add additional peripheral libraries (PLIBs) to a project and the MCC will generate device-specific code to initialize and control the selected peripherals.

Peripheral Libraries are devices family specific.