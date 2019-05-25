# AWS Athena

## Named Queries

### batch-get-named-query
```
$ aws athena batch-get-named-query
--named-query-ids <value>
```

### create-named-query
```
$ aws athena create-named-query
--name <value>
--database <value>
--query-string <value>
```

### delete-named-query
```
$ aws athena delete-named-query
[--named-query-id <value>]
```

### get-named-query
```
$ aws athena get-named-query
--named-query-id <value>
```

### list-named-queries
```
$ aws athena list-named-queries
```

### get-query-results
```
$ aws athena get-query-results
--query-execution-id <value>
```

## Query Execution

### batch-get-query-execution
```
$ aws athena batch-get-query-execution
--query-execution-ids <value>
```

### get-query-execution
```
$ aws athena get-query-execution
--query-execution-id <value>
```

### list-query-executions
```
$ aws athena list-query-executions
```

### start-query-execution
```
$ aws athena start-query-execution
--query-string <value>
```

### stop-query-execution
```
$ aws athena stop-query-execution
```

## Work Group

### create-work-group
```
$ aws athena create-work-group
--name <value>
```

### delete-work-group
```
$ aws athena delete-work-group
--work-group <value>
```

### get-work-group
```
$ aws athena get-work-group
--work-group <value>
```

### list-work-groups
```
$ aws athena list-work-groups
```

### update-work-group
```
$ aws athena update-work-group
--work-group <value>
```

## Resource Tagging

### list-tags-for-resource
```
$ aws athena list-tags-for-resource
--resource-arn <value>
```

### tag-resource
```
$ aws athena tag-resource
--resource-arn <value>
--tags <value>
```

### untag-resource
```
$ aws athena untag-resource
--resource-arn <value>
--tag-keys <value>
```
