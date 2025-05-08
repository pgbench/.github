No association with postgresql, just created this organisation to fill/publish with benchmark results.

# pgbench: PostgreSQL Version Benchmarking  

## Overview  
`pgbench` is a PostgreSQL benchmarking initiative that systematically evaluates multiple PostgreSQL versions, from 11 to the latest beta release. By running standardized `pgbench` tests across versions, we aim to provide performance insights and trends over time, helping DBAs and developers make informed decisions about PostgreSQL upgrades.  

## Goals  
- Benchmark PostgreSQL versions from 11 to the latest beta.  
- Publish performance metrics and trends for community reference.  
- Provide reproducible benchmarking methodologies.  

## Methodology  
We use the `pgbench` tool with consistent configurations across all tested versions. Performance results are gathered and analyzed to highlight improvements, regressions, and behavioral changes between versions.  

### Benchmark Configuration  
- Standard `pgbench` workload.  
- Custom scripts for automation and data collection.  
- Comparative analysis across versions.  

## How to Contribute  
If you're interested in contributing:  
1. Fork the repository and clone locally.  
2. Set up PostgreSQL instances for multiple versions.  
3. Run benchmarks using provided scripts.  
4. Submit pull requests with results and analyses.  

## Results & Insights  
Published benchmark results will be available in the repository. Follow updates to stay informed on PostgreSQL performance trends.  

## Contact  
For questions or contributions, open an issue or connect via [GitHub Discussions](https://github.com/pgbench).  
