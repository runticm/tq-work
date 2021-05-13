hello-world
===========

## Running locally

Build and run using Docker Compose:

	$ git clone https://github.com/runticm/tq-work.git
	$ cd tq-work/
	$ docker-compose up
	$ localhost:80


## Deploying to ECS

	$ In AWS create key pair (if you already have it skip it)
	$ After download change permissions
	$ chmod 400 <key_name>
	# git clone https://github.com/runticm/tq-work.git
	$ cd tq-work/
	$ In AWS account run this template <ecs-cluster.template>, set name to EcsClusterStack and select key name. All other settings leave default

Hello world
