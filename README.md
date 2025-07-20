# USB Device Security Manager 🔐

A real-time USB protection tool developed in Python that scans USB drives when plugged in, detects threats using both **signature-based** and **machine learning-based detection**, encrypts safe files, and alerts the user on threats.

## 📚 Project Report
- See `USB_Device_Security_Manager_Report.pdf` for complete documentation.

---

## 🛠 Features

- Real-time USB monitoring
- Detect known & unknown malware
- Encrypts good files
- Quarantine malicious files
- Sends alert pop-ups
- Auto-update & rollback support (planned)
- Future: VirusTotal integration, cloud logs, GUI (PyQt5)

---

## 🧪 Modules

| File | Description |
|------|-------------|
| `usb_monitor.py` | Detect USB drive insertion |
| `signature_scanner.py` | Detect threats using known virus signatures |
| `ml_detector.py` | Use ML to detect unknown malware |
| `encryption_module.py` | Encrypt safe files |
| `quarantine_manager.py` | Move bad files to quarantine |
| `alert_popup.py` | Show real-time alerts |
| `updater.py` | Update and rollback support |

---

## 💻 Install & Run

```bash
pip install -r requirements.txt
python source/usb_monitor.py
