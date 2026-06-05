# Welcome to the Lorasis Demo!

The terminal on your right is a fresh, isolated Ubuntu Linux VM. 

In this scenario, we will install the Lorasis Security Agent and watch it report back to the central dashboard.

### 1. Log in to the Dashboard
First, open the Lorasis Staging Dashboard in a new tab:
* **URL**: [https://staging.lorasis.io](https://staging.lorasis.io)
* **Email**: `demo@lorasis.io`
* **Password**: `DemoPassword123!`

### 2. Install the Agent
Click the **Deploy Agent** button in the dashboard to generate an installation command, or use the one below and substitute your token:

```bash
curl -fsSL https://api.staging.lorasis.io/install.sh | sudo bash -s -- --token=YOUR_TOKEN_HERE
```

Once installed, return to the dashboard's **Inventory** tab to see this machine appear!
