# Oozie with actions: spark and hdfs-move

### Oozie commands

```
oozie job -oozie http://sandbox-hdp.hortonworks.com:11000/oozie -D oozie.wf.application.path=hdfs://sandbox-hdp.hortonworks.com:8020/user/root/workflow.xml -D oozie.use.system.libpath=true -run

oozie job -oozie http://sandbox-hdp.hortonworks.com:11000/oozie -info {id}

oozie job -oozie http://sandbox-hdp.hortonworks.com:11000/oozie -log {id}

oozie job -oozie http://sandbox-hdp.hortonworks.com:11000/oozie -kill {id}
```

### Input-Output

![HDFS input](/images/hdfs-ls-input.png)

![HDFS output](/images/hdfs-ls-output.png)