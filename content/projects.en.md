+++
type = "staticpage"
layout = "projects"
+++
# Projects
Sometimes I actually like a project I've worked on, and it may appear right here on this page.

## Dylans.blog
After dozens of attempts and redesigns I've finally managed to launch my blog, in the end going with an existing theme seemed to be the best option. I have done a few alterations to the theme to make it more my own.

The blog, of course, was built with Hugo and hosted on Cloudflare Pages. This used to be done with their built-in Git integration, but I've since moved it over to GitHub Actions as it allows for more flexibility. The GitHub action installs Wrangler and uses it to upload the files. I found this more efficient than the official GitHub Action for Cloudflare Pages as this method allows the NPM packages (of which Wrangler is one) to be cached.

The site can be visited here: [dylans.blog](https://dylans.blog)  
The source can be found on {{<extlink url="https://github.com/dylantic/dylans-blog" text="GitHub" >}}.

## Blogimagegen
Actually my first functional Go project now that I think about it. Mostly copied from a blogpost but simplified and turned into a CLI tool.  
I found making post images for posts on dylans.blog to be cumbersome. This tool makes consistent images and allows me to set parameters, so I can change what is generated at runtime.

The source can be found on {{<extlink url="https://github.com/dylantic/blogimagegen" text="GitHub">}}

## B2
This one is very much still a work in progress. I found {{<extlink url="https://wiki.nikiv.dev/" text="this project">}} online and really wanted to do something similar. Just a repository of everything I know. I've decided on the name "B2" which makes it sound like a hip new AWS service, but it's actually just "Brain 2". 

I did want the same kind of layout, which I found in the {{<extlink url="https://mcshelby.github.io/hugo-theme-relearn/index.html" text="Relearn theme" >}} for Hugo. It has a lot of functionality I don't want/need or that I want to reimplement. I expect that to be done pretty soon.

My only struggle with this project is that I want to strike a balance between getting it out there soon and having *enough* content. Maybe that's silly since it's a living document.

## SSL Certificate tools in Go
Not much to show for it yet, but I am working on writing some tooling for checking up on and managing SSL certificates and configuration. I've been working in web hosting professionally since 2017 and SSL certificates have been a hot topic for as long as I can remember. Anything I can personally do to make it less of a pain to manage them is a win.