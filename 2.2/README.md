improved-pending-tasks-output.patch: this patch improves the output of nodetool compactionstats by showing pending compactions per table rather than a simple number.  

cassandra-13015.patch: this patch backports additional compaction metrics that were added to cassandra 4.0 to track the number of times sstables were removed from compaction tasks (scope was reduced)
