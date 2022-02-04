# Update Frequency for Sensor Data and Logs on Gateways

Although all gateways have similar schedule for pushing their sensor data and logs, the battery-powered gateways which usualy have less stable internet connections are more prone to miss a push or two per day due to connection problems. That may cause multiple UP/DOWN notifications if we check them for all the updates. So, for the AC-powered gateways and battery-powered gateways, we should check for the updates twice a day and once a day respectively and send notifications if they are not updated in that period.
