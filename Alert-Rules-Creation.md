1. Create new git branch from existing repo.
2. Move to branch to not affect master branch.
3. Get and confirm the resource(s) names and that they are working.
4. Get and confirm the resource subscription.
5. Confirm the resource Application Code using Azure tags.
6. Move to Monitoring Alert Descriptors > data > XX > manual directory
7. Create a .JSON file representing the alert rule with a clear label.
8. Copy a prior Alert Descriptor .JSON object to make things easier and paste it inot the new .JSON file.
9. Remove and replace details so the alert rule fits the requirments. 
10. Duplicate this process for as many objects as needed.
11. Convert the Alert Rules to an ARM template by running the Monitoring ARM Files Generator pipeline.


Azure Monitor Supported Metrics: https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/metrics-supported
