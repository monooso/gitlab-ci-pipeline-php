# GitLab CI Pipeline for PHP
Docker container for testing [Laravel][laravel] projects in the GitLab CI pipeline.

[The "parent" image][daddy] takes care of the heavy lifting, this just adds the `ext-gmp` extension. Use the upstream image, where possible.

[daddy]: https://github.com/edbizarro/gitlab-ci-pipeline-php/
[laravel]: https://laravel.com/

## Building ##
Build the Docker images from the repository root. For example:

```bash
docker build -t monooso/gitlab-ci-pipeline-php:7.3 -f Dockerfile-7.3 .
```
