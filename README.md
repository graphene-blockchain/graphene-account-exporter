# GRAPHENE ACCOUNT HISTORY EXPORTER

Demo: https://history.gph.ai

The repo host an account exporter for Graphene, highly demanded by the community.

All graphene related stuff is at `index.php`, the rest is just dependencies to make the form looks a bit prettier.

The exporter will use an ElasticSearch Wrapper instance(https://github.com/graphene-blockchain/graphene-explorer-api) connected to a bitshares node with elasticsearch plugin to pull account operation history and present it in CSV format.
