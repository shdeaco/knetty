# knetty
knetty
A pod monitoring service.

In kubernetes it is difficult to monitor individual pods within a kubernetes resources (such as deployments, statefulsets and daemonsets). Often pods will restart or become unavailable without maintainers being notified about these events. Knetty provides a service that is able to monitor individual pods.  

Knetty services include:
Record individual pod API endpoints
Record outages, restarts and uptime
Multicluster monitoring
Alerts and notifications

Knetty architecture:
Using Helm you are able to deploy either an agent or server. The server provides an ingress for the agents to connect to and record the activity that the agents are streaming. The agent then connects to the server through the ingress. This allows the agents to monitor multiple services on many clusters.

Install guide:
Coming soon…
