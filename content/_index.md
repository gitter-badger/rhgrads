+++
title = "DocDock Theme for Hugo"
description = ""
+++

# Hugo docDock theme - Speedtest
[Hugo-theme-docdock ](https://github.com/vjeantet/hugo-theme-docdock) is a theme for Hugo, a fast and modern static website engine written in Go. Hugo is often used for blogs, **this theme is fully designed for documentation.**

This theme is a partial porting of the [Learn theme of matcornic](https://github.com/matcornic/hugo-theme-learn). and its default style "flex" comes from [facette.io](https://github.com/facette)'s documentation.

## Contribute to this documentation
Feel free to update this content, just click the **Edit this page** link displayed on top right of each page, and pullrequest it


## Documentation website
This current documentation has been statically generated with Hugo with a simple command : `hugo -t docdock` -- source code is [available here at GitHub](https://github.com/vjeantet/hugo-theme-docDock)


Automatically published and hosted thanks to [Netlify](https://www.netlify.com/).

Read more about [Automated HUGO deployments with Netlify](https://www.netlify.com/blog/2015/07/30/hosting-hugo-on-netlifyinsanely-fast-deploys/)


<script src="https://identity.netlify.com/v1/netlify-identity-widget.js"></script>

<script>
  if (window.netlifyIdentity) {
    window.netlifyIdentity.on("init", user => {
      if (!user) {
        window.netlifyIdentity.on("login", () => {
          document.location.href = "/admin/";
        });
      }
    });
  }
</script>
