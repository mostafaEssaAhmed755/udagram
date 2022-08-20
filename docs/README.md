# Endpoints

[API](http://udagram-api-dev.eba-dxnbm6mr.us-east-1.elasticbeanstalk.com/)

[Frontend](http://udagram-frontend1212.s3-website-us-east-1.amazonaws.com)

# infrastructure

1. RDS: for database
1. Elastic Beanstalk: for Backend API
1. S3 : for hosting frontend

# Pipeline process

1. build
1. hold
1. deploy

## build

1. setup node.js
1. install frontend
1. install api
1. frontend lint
1. build frontend
1. build api

## deploy

1. setup node.js
1. setup Elastic Beanstalk Cli
1. setup AWS Cli
1. configure AWS Access Key
1. deploy forntend and api
