1111
2222
3333

<a href="https://wyfeitian.github,io?wyfeitian/" class="github-corner" aria-label="View source on GitHub"><svg width="80" height="80" viewBox="0 0 250 250" style="fill:#FD6C6C; color:#fff; position: absolute; top: 0; border: 0; right: 0;" aria-hidden="true"><path d="M0,0 L115,115 L130,115 L142,142 L250,250 L250,0 Z"></path><path d="M128.3,109.0 C113.8,99.7 119.0,89.6 119.0,89.6 C122.0,82.7 120.5,78.6 120.5,78.6 C119.2,72.0 123.4,76.3 123.4,76.3 C127.3,80.9 125.5,87.3 125.5,87.3 C122.9,97.6 130.6,101.9 134.4,103.2" fill="currentColor" style="transform-origin: 130px 106px;" class="octo-arm"></path><path d="M115.0,115.0 C114.9,115.1 118.7,116.5 119.8,115.4 L133.7,101.6 C136.9,99.2 139.9,98.4 142.2,98.6 C133.8,88.0 127.5,74.4 143.8,58.0 C148.5,53.4 154.0,51.2 159.7,51.0 C160.3,49.4 163.2,43.6 171.4,40.1 C171.4,40.1 176.1,42.5 178.8,56.2 C183.1,58.6 187.2,61.8 190.9,65.4 C194.5,69.0 197.7,73.2 200.1,77.6 C213.8,80.2 216.3,84.9 216.3,84.9 C212.7,93.1 206.9,96.0 205.4,96.6 C205.1,102.4 203.0,107.8 198.3,112.5 C181.9,128.9 168.3,122.5 157.7,114.1 C157.9,116.9 156.7,120.9 152.7,124.9 L141.0,136.5 C139.8,137.7 141.6,141.9 141.8,141.8 Z" fill="currentColor" class="octo-body"></path></svg></a><style>.github-corner:hover .octo-arm{animation:octocat-wave 560ms ease-in-out}@keyframes octocat-wave{0%,100%{transform:rotate(0)}20%,60%{transform:rotate(-25deg)}40%,80%{transform:rotate(10deg)}}@media (max-width:500px){.github-corner:hover .octo-arm{animation:none}.github-corner .octo-arm{animation:octocat-wave 560ms ease-in-out}}</style>


# Header config
title: 教育培训
author: 小飞
logo_img: /img/Kaze.png # put the logo on the ${blog_path}/source/img/${picname}.png or use urls
author_img: /img/Kaze.png
author_description: designed by theme-kaze
#------------------------
# Navbar config
#------------------------
menus:
  home: /
  archive: /archives
  tags: /tags
  categories: /categories
  about: /about
  friends: /links
  # artitalk: /shuoshuo # You can uncomment to add this route

about:
  description: description
  social_links:
    # - { icon: icon, link: your link }

#------------------------
# Links
#------------------------
links:
  # name:
  #   url: https://example.com
  #   avatar:
  #   description:
  #------------------------
  # tip: if you want to use QQ avatar without giving away your QQ number,
  # you can use this api to get an encrypted url:
  # https://ptlogin2.qq.com/getface?appid=1006102&imgtype=3&uin=${yourQQNumber}
  # and use the encrypted url in the json
  #------------------------

#------------------------
# Post
#------------------------
toc:
  showListNumber: false
  maxDepth: 6
  minDepth: 1

copyright:
  enable: true
  writer: # if writer is empty we will use config.author as writer
  declare: 本博客所有文章除特别声明外，均采用<a target="_blank" rel="noopener" href="https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh">CC BY-NC-SA 4.0 协议</a>。转载请注明出处！
  style: warning # the style uses note warning | danger | primary | info | success

search:
  enable: true
  path: search.json
  field: posts
  searchContent: true

og:
  enable: true
  title: true
  url: true
  image: true
  description: true
  article: true
#------------------------
# Footer
#------------------------
footer:
  copyYear: 2020
  # if showPoweredBy is ture, 'Powered by Hexo' will be seen on the footer
  showPoweredBy: true
  # if showThemeName is ture, 'Theme - Kaze' will be seen on the footer
  showThemeName: true
  #------------------------
  # Record config
  # please put the gov image in ${yoursite}/img/beian.png
  RecordInfo: "" # your Record info such as '某ICP备xxx号'
  govRecordInfo: "" # your gov record info such as '某公网安备xxx号'
  govRecordUrl: "" # your gov record url
  #------------------------
  # pv / uv statistics config
  #------------------------
  statistics:
    enable: false
    type: busuanzi # now version only supports busuanzi
    pv:
      enable: true
      style: 本站总访问量{}次 # the style will be shown as $1{pv}$2
    uv:
      enable: true
      style: 本站总访客数{}次 # the style will be shown as $1{uv}$2

widgets:
  showWidgetsMobiles: "none"
#------------------------
# animation config
#------------------------
# if scrollUpAnimation is true, there will be scroll-up animation.
scrollUpAnimation: true

#------------------------
# comment config
#------------------------
comment:
  enable: false
  type: valine # valine | gitalk | livere | disqus | we recommend valine | waline
  # gitalk config details can see in https://github.com/gitalk/gitalk/blob/master/readme-cn.md
  # waline config details can see in https://waline.js.org
  valine:
    appId:
    appKey:
    placeholder: Just go go
    path: window.location.pathname
    avatar: mp
    meta: ["nick", "mail", "link"]
    pageSize: 10
    visitor: false
    highlight: true
    recordIP: false
    serverURLs: # leancloud国内自定义域名
    emojiCDN:
    emojiMaps: null
    enableQQ: false
    requiredFields: []
  gitalk:
    clientID:
    clientSecret:
    repo:
    owner:
    admin:
    id: location.href
    distractionFreeMode: false
    # en | zh-CN | zh-TW
    language: navigator.language || navigator.userLanguage
    labels: ['Gitalk']
    perPage: 10
  livere:
    uid:
  waline:
    serverURL:
    placeholder: Just go go
    path: window.location.pathname
    avatar: mp
    meta: ["nick", "mail", "link"]
    pageSize: 10
    visitor: false
    highlight: true
    emojiCDN:
    emojiMaps: null
    enableQQ: false
    requiredFields: []
    anonymous: true

#------------------------
# latex config
#------------------------
# choose true to use latex by mathjax or katex
# warning: latex rendering will put lots of loading burden on page loading
latex:
  enable: false
  engine: mathjax # mathjax | katex
  # for better rendering effect, when you choose mathjax, you can use it directly but you will lose some effect
  # so you can use hexo-renderer-kramed
  # when you choose katex, you must use hexo-renderer-markdown-it-plus or other render engine
  global: false
  # when you choose false, you can use latex by `latex: true` in post front-matter

#------------------------
# lazyload config
#------------------------
lazyload:
  enable: true
  loadingImg:

#------------------------
# plugins config
#------------------------
lightbox:
  enable: true
# If your hexo version is below 5.0.0, please upgrade first to use this config
# we support eight highlight themes, you can go to prism website (https://prismjs.com) for more information
# theme: default | coy | dark | funky | okaidia | solarizedlight | tomorrow | twilight
prism:
  theme:
# show the number of words in posts
wordcount:
  enable: true
# Analytics config
analytics:
  enable: false
  type: google # google
  google:
    id: # you can see more information in https://analytics.google.com/
# Doc：https://artitalk.js.org/
artitalk:
  enable: false
  appId: 
  appKey: 
#------------------------
# minify config
# css minify uses autoprefixer and clean-css
# javascript minify uses uglify-es
# html minify uses html-minifier
#------------------------
minify:
  enable: false
  css: true
  js: true
  html: true
#------------------------
# theme design config
#------------------------
# the config of theme colors and styles
# you can modify these presets to design different styles
color:
  text-color: "#3c4858"
  text-strong-color: "#2f3d4e"
  text-light-color: "#909faf"
  divider-color: "#e6e8ee"
  title-color: "#475b6d"
  link-color: "#3273dc"
  link-hover-color: "#6596e5"
  info-text-color: "#909faf"
  widget-background-color: "#fff"
  body-background-color: "#f2f5f8"
  border-color: "#e1e4e9"
  pre-color: "#2d2d2d"
  code-color: "#50687c"
  code-background-color: "#e9eaf0"

font:
  font-size: 16px # global font-size
  font-family: '-apple-system,BlinkMacSystemFont,"Segoe UI","Helvetica Neue","PingFang SC","Microsoft YaHei",sans-serif' # global font-family

#------------------------
# cdn config
#------------------------
cdn:
  mathjax: //cdn.jsdelivr.net/npm/mathjax@3.0.5/es5/tex-svg.js
  katex: //cdn.jsdelivr.net/npm/katex@0.11.1/dist/katex.min.css
  gitalk:
    css: //cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.css
    js: //cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.min.js
  valine: //unpkg.com/valine/dist/Valine.min.js
  livere: //cdn-city.livere.com/js/embed.dist.js
  waline: //cdn.jsdelivr.net/npm/@waline/client/dist/Waline.min.js
  baguetteBox: /js/lib/lightbox
  lozad: /js/lib/lozad.min.js
  prism: /js/lib/prism/
  busuanzi: /js/lib/busuanzi.min.js
  artitalk: https://cdn.jsdelivr.net/npm/artitalk
  md5: /js/lib/md5.min.js




