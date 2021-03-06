---
title: Write Unavailables
brief: Count of write unavailables since server start
metric_type: cumulative_counter
---
### Write Unavailables

> Count of write unavailable since server start

A non-zero value means that insufficient replicas were available to fulfil a write request at the requested consistency level.

This typically means that one or more nodes are down. To fix this condition, any down nodes must be restarted, or removed from the cluster.
