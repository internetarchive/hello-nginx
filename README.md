# hello-nginx
nginx superfast "hi world" demo
---

Super fast nginx default container to show full CI/CD w/ a GitHub repo.

You'll be up and running in seconds.

@see [.github/workflows/cicd.yml](.github/workflows/cicd.yml) for a nice GitHub Actions default CI/CD setup, where we simply customize the `NOMAD_VAR_PORTS` variable to tell nomad the main webserver is listening on port 80.
