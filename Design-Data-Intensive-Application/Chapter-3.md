### Log Structured
- log: an append-only sequence of records
- log structured database: 
    - do not update the original data storage, everything a write coming, put it into the new segment
    - background thread merge the key-value from different segments
