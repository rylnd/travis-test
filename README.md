To subscribe your endpoint to issue comments:

    curl -u 'USERNAME:PASSWORD' https://api.github.com/repos/USERNAME/YOUR_REPO/hooks -X POST -d '{"name":"web","active":true,"config":{"url":"YOUR_ENDPOINT"},"events":["push","pull_request","issue_comment"]}'
