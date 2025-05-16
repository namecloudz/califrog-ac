# Califrog Anti-Cheat

Califrog Anti-Cheat is a premium-grade Minecraft anti-cheat plugin that utilizes advanced technology to detect various forms of cheating.

## ✨ Core Features

### 🎯 Advanced Detection Systems
- **Advanced Combat Analysis**
  - KillAura detection through attack pattern analysis
  - Combat reach checking with ping compensation
  - Auto-clicking detection with consistency analysis

- **Network-Level Protection**
  - Packet analysis for manipulation detection
  - Packet rate monitoring
  - Connection analysis for Proxy/VPN detection

- **Machine Learning System**
  - Movement pattern analysis
  - Click pattern analysis
  - Combat pattern analysis
  - Rotation pattern analysis

- **Advanced Inventory Protection**
  - Inventory desync detection
  - Impossible item movement detection
  - Inventory speed checks
  - Drag pattern analysis

- **Advanced Movement Checks**
  - Speed detection with environmental factors
  - Sophisticated flight detection
  - NoFall checks with physics validation
  - Timer hack detection

### 🛡️ Premium Features
- False Positive Prevention System
- Advanced Violation Management
- Staff Notification System
- Detailed Logging System
- Configurable Thresholds
- Permission-based Bypass System

### 🧮 Advanced Algorithms
- Statistical analysis for pattern detection
- Machine learning for anomaly detection
- Vector mathematics for movement validation
- Shannon entropy calculation for randomness detection
- Z-score analysis for outlier detection
- Coefficient of variation analysis

## 📋 System Requirements
- Spigot/Paper 1.8+
- Java 8+
- RAM 512MB+

## ⚙️ Installation
1. Download the latest .jar file
2. Place the file in your plugins folder
3. Restart your server
4. Configure settings in config.yml as needed

## 🔧 Configuration
```yaml
# Detection Thresholds
checks:
  combat:
    reach:
      max_distance: 3.5
    autoclick:
      max_cps: 20
  movement:
    speed:
      max_speed: 0.45
    flight:
      max_air_time: 2.0

# Punishments
punishments:
  warn_threshold: 5
  kick_threshold: 10
  ban_threshold: 15
  punishment_cooldown: 60000 # 1 minute

# Messages
messages:
  prefix: "&c[CAC] &f"
  warn: "&cWarning: Possible cheating detected (%check%)"
  kick: "&cKicked: Cheating detected"
  ban: "&cBanned: Multiple cheat detections"
```

## 🔑 Commands and Permissions
### Commands
- `/cac` - Main command
- `/cac reload` - Reload configuration
- `/cac notify` - Toggle notifications
- `/cac logs <player>` - View violation history

### Permissions
- `cac.admin` - Access to all commands
- `cac.notify` - Receive notifications
- `cac.bypass` - Bypass all checks
- `cac.bypass.<check>` - Bypass specific check

## 📊 Notifications and Logging
- Real-time staff notifications
- Detailed violation logging
- Per-player violation tracking
- Detection confidence analysis

## 🤝 Support
If you encounter issues or need assistance:
- Open an Issue on GitHub
- Join our Discord Server
- Contact staff directly

## 📝 License
Copyright © 2024 Califrog Anti-Cheat
All rights reserved 
