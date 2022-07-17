## week 1 results

Not full yet, optional part is comming soon\
Also need to refactor notebooks to split in different files

**Two towers trained only on small sample due to resource limit. Also only one epoch.**\
**CG based on Price and user intent draws candidates randomly after filtering**

| Metric  | random |popular| user intent | price | Two tower dafault | Two tower with features|
| ------------- | ------------- |------------- |------------- |------------- |------------- |------------- |
| Recall@100  | 0.015 | 0.013  | 0.004  | 0.013  | 0.056  | Content Cell  |
| Recall@1000  | 0.06  | 0.23  | 0.15  | 0.093  | 0.195  | Content Cell  |
