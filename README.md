## Wiz Plugin Demo

This repo contains a demo [Buildkite](https://buildkite.com/home) pipeline that makes use of the [Wiz Buildkite Plugin](https://github.com/buildkite-plugins/wiz-buildkite-plugin) to perform a Container Image Scan using the plugin.

There are other options available, so be sure to check out the repo's README for more options if you're keen on using this.


### Configuration

- Fork the repo
- Make sure that you have set `WIZ_SECRET` and `WIZ_API_ID` in your agent [environment](https://buildkite.com/docs/pipelines/security/managing-secrets#exporting-secrets-with-environment-hooks) or via [Buildkite Secrets](https://buildkite.com/docs/pipelines/buildkite-secrets)
- Create a new pipeline, and link it to your fork.
- Create a new build! 🚀🚀🚀