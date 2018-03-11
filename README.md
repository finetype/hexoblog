stuff is going well, here's the skinny:

-navigation is still wonky, work on that.
-look at configuration options more: https://hexo.io/docs/configuration.html
-look at cool stuff: https://github.com/hexojs/awesome-hexo#showcases

to make new post:

`hexo new draft "My Blog Post"`

to run:

`hexo server -o`

to publish:

`hexo publish My-First-Blog-Post`

to make a static version:

`hexo generate`

then, to publish to the world:

`surge public/ code.blog.kylebaker.io`

if there's anything that doesn't transfer (theme customizations), delete public/ and re-run `hexo generate`

(might try to set up `hexo deploy` eventually, maybe.)
