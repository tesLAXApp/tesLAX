# tesLAX - CANBus Explorer App for iOS

tesLAX is a CANBus Explorer and visualization tool.  While it may be useful for other vehicles, such as the Model S and X, tesLAX was specifically designed with the Tesla Model 3 in mind.

This repository is for issue tracking and publishing files that may be of use to tesLAX users.

## About tesLAX Connectivity

** tesLAX can connect to an OBDLink MX+ bluetooth adapter to show live CANBus data from your vehicle. Additional wiring, and installation is necessary.  Damage done to your vehicle may not be covered by vehicle warranty. Proceed at your own risk. **

## Other FREE features of the app include:

- Predefined visualization with many useful signals for the Tesla Model 3, S, and X.
- Out of the box signal database with currently known signals from the Tesla Model 3.
- Designed to analyze and visualize CANBus data with 11-bit message identifiers.
- Works with the ScanTool OBDLink MX+ (required for iOS compatibility, this is the ONLY supported accessory)
- Playback CANBus log files from iCloud Drive if you don't have a compatible bluetooth adapter or want to explore a previous log.  Support raw TXT logs and the CANBus ASC file format.

## With an "Extended Release" purchase or subscription:

- Configure the visualization by choosing signals from the included signals database.

## For pros, and tinkerers, an "Extra Strength" purchase or subscription unlocks additional features:

- Modify the signal database allowing you to create and explore new messages and signals.  Maintain your own signal configuration as the vehicle manufacturer changes the available messages and signals.
- Ability to import DBC files (containing signal definition information) from iCloud Drive
- A "Binary Matrix" view of a message or signal for reverse engineering data streams,.
- Use javascript code to calculate a result value from the raw message bytes (or other defined signals within the same message)

## Important information

This software is not affiliated with or endorsed by Tesla Motors or any vehicle manufacturer.

This app accesses data streams that are not documented or supported by the vehicle manufacturer.   If the vehicle manufacturer decides to change the data stream, then this app may display incorrect information.  If the vehicle manufacturer removes data, then some or all functionality of the app may cease to work.  Many signals in the signal database may be from previous versions of the vehicle operating software (such as the Model 3 cell voltages, which were removed in a software update many updates ago)

You are responsible for all risks of installing and using 3rd party hardware in your vehicle.  Proceed at your own risk.

Do not use tesLAX while driving.  Please obey all traffic laws and do not drive while distracted.

You accept full and unconditional responsibility for the use of this software. All About Jake, LLC is not responsible for any consequences of using this software, including any damage to your vehicle, loss, damage to property, personal injury, or violation of law that may occur in connection with using this application.  Obey all laws and respect the privacy of others. THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.  The author(s) and copyright holders shall not be liable for any damages, even if advised beforehand of the possibility of such damages.

