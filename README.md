# Cache Manager Redis and IoRedis Stores

This is a mono repo for the Cache Manager Redis and IoRedis stores. These are the legacy stores for `v5` as we are now moving forward with [Keyv](https://keyv.org) for redis. This repo is a collection of packages that are used to store cache data in Redis and IoRedis. The packages are:

| Package | Version | Downloads | Description |
|-------|---------|---------|---------|
| [cache-manager-redis-yet](https://github.com/jaredwray/cacheable/tree/main/packages/cache-manager-redis-yet) | [![npm](https://img.shields.io/npm/v/cache-manager-redis-yet)](https://www.npmjs.com/package/cache-manager-redis-yet) | [![npm](https://img.shields.io/npm/dm/cache-manager-redis-yet.svg)](https://www.npmjs.com/package/cache-manager-redis-yet) | Redis storage adapter for cache-manager |
| [cache-manager-ioredis-yet](https://github.com/jaredwray/cacheable/tree/main/packages/cache-manager-ioredis-yet) | [![npm](https://img.shields.io/npm/v/cache-manager-ioredis-yet)](https://www.npmjs.com/package/cache-manager-ioredis-yet) | [![npm](https://img.shields.io/npm/dm/cache-manager-ioredis-yet.svg)](https://www.npmjs.com/package/cache-manager-ioredis-yet) | IORedis storage adapter for cache-manager. |

# How to Use the Cacheable Mono Repo

* [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md) - Our code of conduct
* [CONTRIBUTING](CONTRIBUTING.md) - How to contribute to this project
* [SECURITY](SECURITY.md) - Security guidelines and supported versions

## Open a Pull Request

You can contribute changes to this repo by opening a pull request:

1) After forking this repository to your Git account, make the proposed changes on your forked branch.
2) You will need `docker` installed and running on your machine. Once it is installed run `pnpm test:services:start` to start the services needed for testing.
3) Run tests and linting locally.
	- Run `pnpm i && pnpm test`.
4) Commit your changes and push them to your forked repository.
5) Navigate to the main `cache-manager-stores` repository and select the *Pull Requests* tab.
6) Click the *New pull request* button, then select the option "Compare across forks"
7) Leave the base branch set to main. Set the compare branch to your forked branch, and open the pull request.
8) Once your pull request is created, ensure that all checks have passed and that your branch has no conflicts with the base branch. If there are any issues, resolve these changes in your local repository, and then commit and push them to git.
9) Similarly, respond to any reviewer comments or requests for changes by making edits to your local repository and pushing them to Git.
10) Once the pull request has been reviewed, those with write access to the branch will be able to merge your changes into the `cacheable` repository.

If you need more information on the steps to create a pull request, you can find a detailed walkthrough in the [Github documentation](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork)

## Post an Issue

To post an issue, navigate to the "Issues" tab in the main repository, and then select "New Issue." Enter a clear title describing the issue, as well as a description containing additional relevant information. Also select the label that best describes your issue type. For a bug report, for example, create an issue with the label "bug." In the description field, Be sure to include replication steps, as well as any relevant error messages.

If you're reporting a security violation, be sure to check out the project's [security policy](./SECURITY.md).

Please also refer to our [Code of Conduct](./CODE_OF_CONDUCT.md) for more information on how to report issues.

## Ask a Question

To ask a question, create an issue with the label "question." In the issue description, include the related code and any context that can help us answer your question.

## License

[MIT © Jared Wray](LICENSE)
