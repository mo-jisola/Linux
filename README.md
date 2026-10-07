# Kali Linux System & Network Analysis

A structured documentation of basic **Kali Linux system administration, system information gathering, network connectivity testing, and command-line analysis**.

This repository contains the work completed for a Kali Linux practical assignment, including system configuration details, hardware/resource information, Linux kernel information, network latency testing, packet-loss analysis, IP-address identification, and command behavior observations.

---

## 📌 Project Overview

The purpose of this project is to demonstrate practical familiarity with the Kali Linux command line and fundamental system/network troubleshooting concepts.

The assignment is divided into two primary sections:

1. **System Information & Configuration**
2. **Network Connectivity & Analysis**

The work was performed in a Kali Linux environment using the `kali` user and hostname.

---

## 🗂️ Project Structure

```text
.
├── README.md
└── Kali Assignment.pdf
```

> The PDF contains the original assignment documentation and recorded results.

---

# 🖥️ Part 1 — Kali Linux System Information

## Step 1 — System Identity

The Kali Linux environment was examined to identify the active user, hostname, and working directory.

| Property       | Value        |
| -------------- | ------------ |
| Username       | `kali`       |
| Hostname       | `kali`       |
| Home Directory | `/home/kali` |

These details establish the basic identity and filesystem context of the Kali Linux environment.

### Environment

```text
Username: kali
Hostname: kali
Directory: /home/kali
```

---

## Step 2 — System Resources

The system's available memory, disk space, and Linux kernel version were recorded.

| System Property      | Recorded Value       |
| -------------------- | -------------------- |
| RAM                  | 1.9 GiB              |
| Available Disk Space | 1.0 GiB              |
| Linux Kernel         | Linux Kali 6.19.14-1 |
| Kernel Date          | 2026-05-05           |

The recorded kernel information identifies the Linux kernel running in the Kali environment.

### System Summary

```text
RAM:
1.9 GiB

Available Disk Space:
1.0 GiB

Linux Kernel:
Linux Kali 6.19.14-1

Kernel Release Date:
2026-05-05
```

---

# 🌐 Part 2 — Network Connectivity & Analysis

The second part of the assignment focused on network connectivity and basic network measurement.

## Step 1 — Connectivity Test

The recorded network test produced the following results:

| Metric                  |    Result |
| ----------------------- | --------: |
| Average Round-Trip Time | 19.171 ms |
| Packet Loss             |        0% |

The average round-trip time represents the average time required for packets to travel to the destination and return. A packet-loss result of `0%` indicates that no packet loss was recorded during the documented test.

### Results

```text
Average round-trip time: 19.171 ms
Packet loss: 0%
```

### Interpretation

The recorded test indicates a successful network connection during the test period:

* **19.171 ms average latency** — packets completed the round trip relatively quickly.
* **0% packet loss** — all packets involved in the recorded test were successfully returned.
* Network performance can vary over time depending on Internet conditions, routing, congestion, and local network performance.

---

## Step 2 — IP Address & Command Analysis

The documented IP address was:

```text
142.250.189.142
```

The assignment notes that the round-trip time can vary depending on Internet speed and latency at the time the search/test is performed.

### IP Address

| Property   | Value             |
| ---------- | ----------------- |
| IP Address | `142.250.189.142` |

---

## 🔎 Understanding `C4`

The assignment also documents the meaning of `C4` in relation to the command used during the network/search activity.

According to the assignment:

> `C4` represents how many results the command is expected to generate before stopping by itself.

In practical terms, the value controls the number of results generated before the command terminates automatically.

---

# 📊 Results Summary

The following table provides a consolidated view of the documented results.

| Category                | Result                                               |
| ----------------------- | ---------------------------------------------------- |
| Operating System        | Kali Linux                                           |
| Username                | `kali`                                               |
| Hostname                | `kali`                                               |
| Home Directory          | `/home/kali`                                         |
| RAM                     | 1.9 GiB                                              |
| Available Disk Space    | 1.0 GiB                                              |
| Linux Kernel            | 6.19.14-1                                            |
| Kernel Date             | 2026-05-05                                           |
| Average Round-Trip Time | 19.171 ms                                            |
| Packet Loss             | 0%                                                   |
| Recorded IP Address     | `142.250.189.142`                                    |
| `C4`                    | Number of expected results before automatic stopping |

---

# 🎯 Learning Objectives

This assignment demonstrates several foundational Linux and networking concepts.

### Linux System Administration

* Identifying the current Linux user
* Identifying the system hostname
* Understanding the current filesystem directory
* Inspecting available system memory
* Checking available disk space
* Identifying the Linux kernel version

### Network Administration

* Testing network connectivity
* Measuring round-trip latency
* Identifying packet loss
* Recording an IP address
* Understanding how network results can vary over time

### Command-Line Skills

The exercise also demonstrates how command-line tools can be used to collect system and network information and interpret their output.

---

# 🧪 Environment

The documented environment consists of:

```text
Operating System: Kali Linux
User:             kali
Hostname:         kali
Home Directory:   /home/kali
RAM:              1.9 GiB
Disk Available:   1.0 GiB
Kernel:           6.19.14-1
```

---

# 📈 Network Test Results

```text
Average Round-Trip Time: 19.171 ms
Packet Loss:             0%
IP Address:              142.250.189.142
```

These results represent the conditions observed when the assignment was performed. Network latency is not a fixed value and may change depending on network traffic, routing, Internet conditions, and other factors.

---

# 📝 Key Observations

### 1. System Configuration

The Kali environment was running under the `kali` user with `kali` as the hostname. The documented home directory was `/home/kali`.

### 2. Available Resources

The environment had approximately **1.9 GiB of RAM** and **1.0 GiB of available disk space** at the time of documentation.

### 3. Kernel Information

The system was running the documented Linux kernel version:

```text
Linux Kali 6.19.14-1
```

with the recorded kernel date of `2026-05-05`.

### 4. Network Connectivity

The network test recorded an average round-trip time of **19.171 ms** and **0% packet loss**, indicating successful connectivity during the documented test.

### 5. Network Results Can Change

The assignment specifically notes that round-trip time may differ depending on Internet speed and latency at the time the test is performed.

---

# 📚 Documentation

The original assignment documentation is included in this repository:

```text
Kali Assignment.pdf
```

It contains the recorded system information, network results, and observations used to produce this README.

---

# ⚠️ Notes

* System resource values represent the environment at the time of testing.
* Network latency is variable and should not be treated as a permanent measurement.
* The recorded IP address reflects the result documented in the assignment.
* The README intentionally does not add commands or results that were not documented in the original assignment.

---

# 👤 Author

**Mojisola Oloro**

Student ID: `GRC-C26-09-EU-030`

Date of Assignment: `09/22/2026`

---

## 📄 License

This repository is intended primarily for educational and academic documentation.

Unless otherwise specified, the materials in this repository should be considered educational coursework and may not be reused or redistributed without appropriate permission.

