# Perf

# Linux first checks
https://netflixtechblog.com/linux-performance-analysis-in-60-000-milliseconds-accc10403c55

```
uptime # load averages
dmesg | tail # kernel errors
vmstat 1 # overall stats by time
mpstat -P ALL 1 # cpu balance
pidstat 1 # process usage
iostat -xz 1 # disk I/O
free -m # memory usage
sar -n DEV 1 # network I/O
sar -n TCP,ETCP 1 # tcp stats
top # overview (atop for details)
```
