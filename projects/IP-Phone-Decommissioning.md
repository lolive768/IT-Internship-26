# Project: IP Phone Decommissioning, Data Sanitization & Resale Prep

## Summary
This project outlines the end-to-end process for hardware inventorying, factory wiping, and testing a batch of decommissioned enterprise IP phones.

- **Equipment:** 120+ Cisco phones of various models (7942, 7945, etc.)
- **Tools Used:** PoE switch

---

## Technical Scope & Security Compliance

### 1. Data Sanitization Protocols
To ensure organizational security compliance, all devices were cleared and reset:
* **Credential Wipe: Erased stored credentials and server configurations.
* **Factory Reset: Returned devices to stock factory defaults.

---

## Standard Workflow

### Phase 1: Intake & Inventory Documentation
1. Gathered phones from storage.
2. Grouped IP phones by specific model.
3. Gathered required accessories for each phone model (e.g., handset, handset cord, stand, wall mount, power adapter).

### Phase 2: Hardware & Functional Testing
1. Inspected phones for visual damage.
2. Connected each phone to a PoE device to test for proper boot.

### Phase 3: Sanitization & Factory Reset
1. Powered device using a standard PoE switch port.
2. Executed vendor-specific hard factory reset key combinations.
3. Verified wipe by booting device off-network.

### Phase 4: Final Grading
1. Documented functional and non-functional phones within an Excel spreadsheet.

---

## Key Takeaways

- **Layer 2 Power Negotiation:** Understood how IP phones use Layer 2 discovery protocols to negotiate Power over Ethernet (PoE) budgets with switch ports prior to full bootup.
- **Automated Provisioning Workflow:** Understood how DHCP Options redirect booting endpoints to a TFTP server for central configuration management.
- **TFTP Boot Sequence:** Learned how the TFTP service (UDP Port 69) dynamically pairs device MAC addresses with specific configuration files to push extension and network parameters.

---

## Project Impact & Metrics
- **Total Units Processed:** [e.g., 120+ phones]
- **Yield Rate:** [e.g., 90% Resale Ready, 10% non-functional]
- **Data Security:** Compliant, with zero credentials or configurations remaining.
