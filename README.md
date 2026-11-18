# Gemorskos 📰
**The digital backbone of news**

IT infrastructure project for a fictional online newspaper, built for the Database Application Management module.

## 🛠️ Tech Stack

* Virtualization: Proxmox
* Server OS: Windows Server + Linux
* Services: Active Directory, DHCP, DNS, NGINX, MySQL
* Network: Firewall, port forwarding, network segmentation
* Editor: Visual Studio Code
* Version control: GitHub

## 👥 Team

* Hunain Mukhtar
* Buse Shen
* Vladimir Chitac
* Romeo Guntaite
* Ruben Peper
* Mohammed

## 🔀 Git Workflow

We use a **branch-per-person** workflow. The `main` branch is protected only the project leader merges via Pull Requests.

| Branch | Owner |
|--------|-------|
| `main` | Protected (github leader merges only) |
| `hunain` | Hunain Mukhtar |
| `buse` | Buse Shen |
| `vladimir` | Vladimir Chitac |
| `romeo` | Romeo Guntaite |
| `ruben` | Ruben Peper |
| `mohammed` | Mohammed |

```bash
# Clone the repo (once)
git clone <repo-url>

# Create your branch (first time)
git checkout -b <your-name>

# Every work session
git checkout <your-name>
git pull origin main
# ... do your work ...
git add .
git commit -m "Describe what you did"
git push origin <your-name>
```

Then open a **Pull Request** on GitHub and assign it to the project leader.

## 🏫 Course

Database Application Management (DAM) NHL Stenden University of Applied Sciences, 2026–2027
