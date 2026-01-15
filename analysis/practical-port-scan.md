# Practical Alert Analysis: Port Scan

## Alert Description
A network alert indicated multiple connection attempts to different ports from a single source.

## Observations
- Multiple destination ports were targeted
- Traffic originated from an internal IP
- The source host was identified as Nessus

## Analysis
The activity matched characteristics of a port scan. However, the source was a known vulnerability scanning tool.

## Conclusion
This alert was classified as a false positive.

## Why This Was a False Positive
- The source was a legitimate security tool
- The scan was internal and authorized
- No malicious behavior was observed on the destination host

