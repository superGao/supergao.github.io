🤹‍♂️使用方法:
🌇电视/广播图标库：
类 别	调用路径	图标数量	更新时间
📺电视	https://live.fanmingming.com/tv/{频道名称}.png	943个	2024.1.6
📻广播	https://live.fanmingming.com/radio/{频道名称}.png	465个	2023.8.27
⛓️创建您的m3u订阅链接：
下载 demo.m3u 空白示例文件并使用文本编辑软件打开。
https://live.fanmingming.com/tv/m3u/demo.m3u
参考下方示例代码将可用的CCTV1节目源替换为您当地可用的直播源链接，依此类推逐个替换。
#EXTM3U x-tvg-url="https://live.fanmingming.com/e.xml"
#EXTINF:-1 tvg-id="CCTV1" tvg-name="CCTV1" tvg-logo="https://live.fanmingming.com/tv/CCTV1.png" group-title="央视",CCTV-1 综合
可用的CCTV1节目源
此处省略...
若您的直播源支持回看，请将第一行代码替换为：

#EXTM3U x-tvg-url="https://live.fanmingming.com/e.xml" catchup="append" catchup-source="?playseek=${(b)yyyyMMddHHmmss}-${(e)yyyyMMddHHmmss}"
将编辑完成的m3u文件上传到您的Github仓库。
为您的Github仓库开启Pages。
通过播放器订阅您的m3u链接。
关于Github Pages：https://docs.github.com/en/enterprise-cloud@latest/pages/quickstart

🛠️工具
📆EPG接口地址：
https://live.fanmingming.com/e.xml
🏞️Bing每日图片：
https://fanmingming.com/bing
🎞️m3u8下载工具：
https://live.fanmingming.com/m3u8
🆕TXT转M3U格式：
https://live.fanmingming.com/txt2m3u
📄M3U转TXT格式：
Demo🔗 https://fanmingming.com/txt?url=https://live.fanmingming.com/tv/m3u/ipv6.m3u
🌐M3U8 Web Player:
Demo🔗 https://live.fanmingming.com/player/?vurl=https://0472.org/hls/cctv13.m3u8
