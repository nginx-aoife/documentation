---
docs:
files:
   - content/agent/install-upgrade/uninstall.md
   - content/nginx-one/agent/install-upgrade/uninstall.md
---

Complete the following steps on each host where you've installed NGINX Agent:

1. Stop NGINX Agent:

   ```shell
   sudo systemctl stop nginx-agent
   ```

1. To uninstall NGINX Agent, run the following command:

   ```shell
   sudo yum remove nginx-agent
   ```