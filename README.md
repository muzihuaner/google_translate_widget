# google_translate_widget
谷歌翻译网页小部件

### 安装步骤
1.引入CSS (head前)
```html
<link rel="stylesheet" href="https://fastly.jsdelivr.net/gh/muzihuaner/google_translate_widget@main/styles.css">
```

2.引入JS
```html
<script async
        src="https://fastly.jsdelivr.net/gh/muzihuaner/google_translate_widget@main/translate-google.js"></script>

 <script type="text/javascript">
        function googleTranslateElementInit() {
            new google.translate.TranslateElement({
                pageLanguage: 'zh-CN',
                includedLanguages: 'af,ga,sq,it,ar,ja,az,kn,eu,ko,bn,la,be,lv,bg,lt,ca,mk,zh-CN,ms,zh-TW,mt,hr,no,cs,fa,da,pl,nl,pt,en,ro,eo,ru,et,sr,tl,sk,fi,sl,fr,es,gl,sw,ka,sv,de,ta,el,te,gu,th,ht,tr,iw,uk,hi,ur,hu,vi,is,cy,id,yi',
                autoDisplay: false
            }, 'google_translate_element');
        }
 </script>
```

3.引入HTML代码在你需要的位置

```html
   <div id="google_translate_element"></div>
```

