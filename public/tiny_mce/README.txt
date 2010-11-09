更新
====

	1. 加入中文语言包(改用简体）
	   -- 下载 tinymce_lang_pack.zip
	
	2. 修改 tiny_mce\themes\advanced 下的 editor_template_src.js：
	   -- 75 行，theme_advanced_fonts 添加：
	   宋体=宋体;楷体_GB2312=楷体_GB2312;黑体=黑体;方正舒体=方正舒体;仿宋_GB2312=仿宋_GB2312;华文彩云=华文彩云;华文细黑=华文细黑;华文新魏=华文新魏;华文行楷=华文行楷;隶书=隶书;微软雅黑=微软雅黑;幼圆=幼圆;
	   -- 压缩
	java -jar yuicompressor-2.3.6.jar -o editor_template.js --charset UTF-8 --type js editor_template_src.js
	pause

    3. 修改 media/tiny_mce/themes/advanced/langs/zh.js （pre的中文翻译）.
   
-- END --
   