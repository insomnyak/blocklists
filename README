# Blocklists

A collection of custom blocklists for use with [Pi-hole](https://pi-hole.net/) or compatible DNS filtering solutions.  
This repository will grow over time as additional lists are added.  

---

## 📋 Available Lists

### 1. Adult Content Blocklist
- **File:** [`adult-blocklist.txt`](adult-blocklist.txt)  
- **Regex rules:** [`adult-regex.txt`](adult-regex.txt)  
- **Purpose:** Blocks domains and subdomains associated with adult content.
- **Status:** Maintained and updated periodically.  

## 🚀 How to Use with Pi-hole

### Adding a Blocklist
1. Go to the Pi-hole Admin UI.
2. Navigate to **Group Management → Lists**.
3. Add the raw URL for the blocklist.
4. Click **Save and Update Gravity** or run:
 ```bash
 pihole -g
 ```

### Adding Regex Rules
Regex rules cannot be added via Lists. You have two options:
- UI method
    1. Go to Group Management → Domains → Blacklist → Regex.
    2. Paste each line from adult-regex.txt.
    3. Save and re-run pihole -g.