# Kalix12 RDP Tunnel

This repository provides a GitHub Actions workflow to set up a temporary Windows RDP environment using Pinggy for tunneling.

## 🚀 Setup Instructions

1. **Fork this repository** to your own GitHub account.
2. **Go to Settings** $\rightarrow$ **Secrets and variables** $\rightarrow$ **Actions**.
3. **Add the following Secrets**:
   - `PINGGY_AUTH_TOKEN`: Your Pinggy authentication token.
   - `TUNNEL_KEY`: The password for the RDP user.
   - `REMOTE_API`: Your remote management API key.
4. **Add the following Variable**:
   - `TUNNEL_USER`: The username you want to create (e.g., `admin`).
5. **Run the Workflow**:
   - Go to the **Actions** tab.
   - Select **Kalix12-RDP**.
   - Click **Run workflow**.
