# Mining Smells Data
This repository contains smell mining data for 3208 open-source C# projects.

In the "Results" folder, each folder contains individual analysis results for the repository. Each analyzed project in a repository has 5 csv files:
- `<project>`ArchSmells.csv: containing information about detected design smells
- `<project>`DesignSmells.csv: containing information about detected design smells
- `<project>`ImplSmells.csv: containing information about detected implementation smells
- `<project>`ClassMetrics.csv: containing class metrics data
- `<project>`MethodMetrics.csv: containing method metrics data

Additionally, the aggregated results are stored in "aggregatedResult" folder.

This analysis data is produced by Designite (http://www.designite-tools.com).