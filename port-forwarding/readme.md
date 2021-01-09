ubuntu should install 

	apt install socat


the flollwing cmds are equal:

	kubectl port-forward redis-master-765d459796-258hz 7000:6379
	kubectl port-forward pods/redis-master-765d459796-258hz 7000:6379
	kubectl port-forward deployment/redis-master 7000:6379
	kubectl port-forward replicaset/redis-master 7000:6379
	kubectl port-forward service/redis-master 7000:redis
	kubectl port-forward deployment/redis-master :6379
