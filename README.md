# hyperf_micro_merged_log
hyperf微服务日志合并

##定时任务
```1 * * * * root /usr/sbin/logrotate /etc/logrotate.d/hyperf > /dev/null 2>&1```
