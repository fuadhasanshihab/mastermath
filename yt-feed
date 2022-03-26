/**
* Fuad Hasan Shihab
* New feed Layout
* 2022-03-26 13:32:28
*/
(function () {
    // Loader
    var loader=new function(){this.rC=-1,this.r=[],this.add=function(t){this.r.push(t)},this.addTag=function(t,e){var i=document.getElementsByTagName("head")[0],s=t.indexOf(".js")>0?"script":"link",n=document.createElement(s);i.appendChild(n),n.onload=e,n.charset="UTF-8","script"===s?(n.type="text/javascript",n.src=t):"link"===s&&(n.rel="stylesheet",n.href=t)},this.loadNext=function(){if(this.rC++,this.rC>=this.r.length)this.done();else{var t=this.r[this.rC];this.addTag(t,this.loadNext.bind(this))}},this.done=function(){this.onResourcesLoaded(window.Curator)},this.load=function(t){this.onResourcesLoaded=t,this.loadNext()}};

    // Config
    var config = {"post":{"matchHeights":false,"showComments":false,"showLikes":false,"maxHeight":0,"minWidth":2000,"showTitles":true,"showShare":true,"autoPlayVideos":false,"clickAction":"open-popup","clickReadMoreAction":"open-popup","maxLines":0},"widget":{"template":"widget-carousel","autoPlay":true,"autoLoad":true,"infinite":false,"controlsOver":true,"controlsShowOnHover":true,"speed":90000,"duration":700,"panesVisible":-1,"useCss":true,"moveAmount":0,"easing":null,"autoLoadNew":false,"lazyLoadType":"none"},"popup":{"deepLink":false,"template":"popup","templateWrapper":"popup-wrapper","autoPlayVideos":false},"lang":"en","container":"#curator-feed-new-feed-layout","debug":0,"hidePoweredBy":true,"embedSource":"","forceHttps":false,"feed":{"id":"38ff4f05-8be8-4081-9c9e-05a24d5467fa","apiEndpoint":"https:\/\/api.curator.io","postsPerPage":12,"params":{},"limit":25},"filter":{"template":"filter","showNetworks":false,"showSources":false,"showAll":false,"default":"all","limitPosts":false,"limitPostNumber":0,"period":""},"type":"Panel","theme":"sydney"};
    var colours = {"widgetBgColor":"transparent","bgColor":"#ffffff","borderColor":"#cccccc","iconColor":"#222222","textColor":"#222222","linkColor":"#999999","dateColor":"#000000","footerColor":"#ffffff","tabIndexColor":"#cccccc"};
    var styles = {};

    // Bootstrap
    function loaderCallback () {
        window.Curator.loadWidget(config, colours, styles);
    }

    // Run Loader
    loader.add('https://cdn.curator.io/5.0/curator.embed.css');
    loader.add('https://cdn.curator.io/published-css/38ff4f05-8be8-4081-9c9e-05a24d5467fa.css');

    loader.add('https://cdn.curator.io/5.0/curator.embed.js');

    

    loader.load(loaderCallback);
})();
