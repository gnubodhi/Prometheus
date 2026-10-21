Put the following text into ollama for your choosen model. I would then put the output of the ai into chatGPT and get it to review it's response.

Review the following Ubuntu administration commands without executing them.

For each command, classify it as VALID, INVALID, CONTEXT_DEPENDENT or DANGEROUS.

Explain what it actually does, whether it is appropriate for a standard Ubuntu workstation, and what additional information would be needed before execution.

Do not invent replacement commands. If uncertain, explicitly say so.

Commands:

1. `journalctl --disk-use-max=10G`
2. `sudo ufw allow 22/tcp`
3. `systemctl list-units --state=enabled`
4. `sudo apt install unattended-upgrades`
5. `sudo adduser workstation-user`
6. `sudo aa-status`
7. `sudo visudo -c`
8. `sudo ufw status verbose`
9. `sudo apt-mark hold openssl`
10. `sudo systemctl reload ssh`

You can also go through the howto's in the json's and ensure the ai outputs workable solutions for your workloads using chatGPT as well. 
