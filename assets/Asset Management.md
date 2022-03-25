| Control Domain  | Sub-Domain  | Control ID  | CCMv4 Domain  | Control  | Confidentiality  | Integrity | Availability  | Additional Direction  |  Reference |  Control Type | Man/Auto/Semi  | Frequency | Device  | Network  | Gateway  | Cloud Service  |   |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|  Asset Management | Inventory Assets  | ASM-01  | DCS  | Schedule a task to update the asset/inventory database at least quarterly.   | Medium  | Medium  | Medium  | Additional information that may be useful to include are the related/associated devices that directly interface with the device. These may include printers, network-attached storage (NAS), mobile applications, USB dongles, and so on. This inventory database should be made available to incident responders as well. The data recorded can prove highly useful during an incident.   | CIS Control 1: Inventory and Control of Hardware Assets https://www.cisecurity.org/controls/  | P | A   | C  | YES  |   | YES  |   |   |
| Asset Management  | Inventory Assets   | ASM-02 | DCS  | Deploy an inventory management system (asset/inventory database) and record details about each IoT device in inventory.  Use this inventory management system to track the hardware, software/firmware, network configurations and location of each device. This includes... 
- device name
- the Virtual Local Area Network (VLAN) that hosts the device
- device physical location
- IP address of the device
- MAC address, software/firmware version data
- vendor detailsassociated Wi-Fi Access Point (AP)
- communication protocols
- whether the device includes cellular capability
- firmware and patch status
- application/library versions
- lost or decommissioned status
- whom the device is assigned  | Medium | Medium  | Medium  | Additional information that may be useful to include are the related/associated devices that directly interface with the device. These may include printers, network-attached storage (NAS), mobile applications, USB dongles, and so on. This inventory database should be made available to incident responders as well. The data recorded can prove highly useful during an incident.   | NIST  SP 1800-5: IT Asset Management
https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.1800-5.pdf   | D | A  | C  | YES |   | YES  |   |   |
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
