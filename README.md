# toggl-vsts-client
Basic console client for toggl, to fill it with Azure DevOps work items.

Planned to do: 
1. tvc start N - where N is a workitem ID in Azure DevOps (VSTS) - starts timer on toggl, with information from workitem.
2. tvc stop - stops currently running item. 
3. tvc afk N [optional: -S -T -L] - Stops currently running item, writes in slack (-S)/teams (-T) that user is afk for given period of time (N). Additionally -L gives information that user has lunch.
4. tvc off [optional: -S -T] - stops timers and writes to slack(-S)/teams(-T) that user left for today.
