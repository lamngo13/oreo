ng deploy --base-href='//oreo\' --repo=https://github.com/lamngo13/oreo.git

Index.html
Base href=”/” for local development but <base href="/oreo/"> for deployment
 otherwise

End url: https://lamngo13.github.io/oreo/

Problem is the page is blank


THIS WORKS:
ng deploy --base-href='//oreo\' --repo=https://github.com/lamngo13/oreo.git
In index.html:
Base href=”/oreo/”
https://lamngo13.github.io/oreo/

Deploying:
https://github.com/angular-schule/angular-cli-ghpages#cname
https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site
