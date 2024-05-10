# Instructions

> git clone -b wildfire git@github.com:fax4ever/distributed-framework.git

> [distributed-framework] go run example/wild-fire-aggregation-query.go 5000 0.01 0.2 max 50 2

Params are: n  edgeProbability faultyProbability query diameterEstimation
Values can be changed on the main / test file

> [distributed-framework] go test -timeout 30s -run ^TestWildFireAggregationQuery$ github.com/krzysztof-turowski/distributed-framework/test
The full algorithm is on the file: https://github.com/fax4ever/distributed-framework/blob/wildfire/aggregation/wild_fire/wild_fire.go