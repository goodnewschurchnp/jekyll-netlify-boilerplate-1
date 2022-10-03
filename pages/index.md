---
layout: default1
title:
permalink: /
---
<style>
body{
    margin: 0 auto;
    font-family: Georgia, Palatino, serif;
    color: #444444;
    line-height: 1;
    max-width: 960px;
    padding: 30px;
}
h1, h2, h3, h4 {
    color: #111111;
    font-weight: 400;
}
h1, h2, h3, h4, h5, p {
    margin-bottom: 24px;
    padding: 0;
}
h1 {
    font-size: 48px;
}
h2 {
    font-size: 36px;
    /* The bottom margin is small. It's designed to be used with gray meta text
     * below a post title. */
    margin: 24px 0 6px;
}
h3 {
    font-size: 24px;
}
h4 {
    font-size: 21px;
}
h5 {
    font-size: 18px;
}
a {
    color: #0099ff;
    margin: 0;
    padding: 0;
    vertical-align: baseline;
}
a:hover {
    text-decoration: none;
    color: #ff6600;
}
a:visited {
    color: purple;
}
ul, ol {
    padding: 0;
    margin: 0;
}
li {
    line-height: 24px;
}
li ul, li ul {
    margin-left: 24px;
}
p, ul, ol {
    font-size: 16px;
    line-height: 24px;
    max-width: 540px;
}
pre {
    padding: 0px 24px;
    max-width: 800px;
    white-space: pre-wrap;
}
code {
    font-family: Consolas, Monaco, Andale Mono, monospace;
    line-height: 1.5;
    font-size: 13px;
}
aside {
    display: block;
    float: right;
    width: 390px;
}
blockquote {
    border-left:.5em solid #eee;
    padding: 0 2em;
    margin-left:0;
    max-width: 476px;
}
blockquote  cite {
    font-size:14px;
    line-height:20px;
    color:#bfbfbf;
}
blockquote cite:before {
    content: '\2014 \00A0';
}

blockquote p {  
    color: #666;
    max-width: 460px;
}
hr {
    width: 540px;
    text-align: left;
    margin: 0 auto 0 0;
    color: #999;
}

</style>

- To build a church website, we use static approach,'static' means opposite to "dynamic' website which has a database, the static website doesn't has a database, which make it less complicated and light-weight,there are similar services like [vercel](https://vercel.com/), [cloudflare pages](https://pages.cloudflare.com/), [github pages](https://pages.github.com) and so on.

> The way is like this: select a template, edit in github.com and host in netlify.com

There is a sample website: [Good News Church Nepal](https://goodnewschurchnp.netlify.app), you can folk and start.

We will start from Information Website:

Local believers use phone to contact Pastor,the church website mainly function as a list of informations, the church serve for local people, the photoes goes to Facebook account or group and leave a link on website. All website are in this setup, there are home page and contact page along with outside Facebook account or group link.

What kind of template should we choose, in my mind there are some ways:

1). responsive, automaticly layout change between mobile and desktop, good for mobile phone user.

2). vertical layout, like an app, good for mobile phone user.

3). a hero image on home page, a hero image is a big picture to show theme of the website.

4). deployed in netlify.com, normally a church website need less update frequency, need simple interface, no need specific administrator, netlify.com suppose to be free to use upto some limitation, Jekyll (a popular Static Site Generator name) was in market in 2008, netlify.com appeared in 2014, so the website deployable in netlify.com means the template can be used free of charge,especially Jekyll template.

We will select different templates, first Jekyll then 11ty, next maybe Next.js, Next maybe Jigsaw. ( All are static statis generator name.)

Follow the [Tutorial](/tutorial) if you want to deploy by yourself.

The most difficult part is how to use the site,how to run the site? We will share in [Opinions](/opinions) section as a starter.

We will introduce data and data analyze according our understanding, that is foundation to use website. We will use Google Analytics.

We will briefly touch domain name, an introduction and how to use domain name, a domain name usually cost about 10 USD a year 

