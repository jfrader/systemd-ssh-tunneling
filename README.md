## Systemd SSH Tunneling

Examples on how to bind ports to another host via SSH using Systemd

## Example

Enable service and start it
`# systemctl enable --now tunnel@example1` 

Stop service
`# systemctl stop tunnel@example1`

Start service
`# systemctl start tunnel@example1`

See status and last log lines
`# systemctl status tunnel@example1`

See logs in real time plus last 200 lines
`# journalctl -xu tunnel@example1 -f -n 200` 
