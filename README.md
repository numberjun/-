作者联系方式(邮箱)：605274498@qq.com <br>

声明: <br>
　　软件均仅用于学习交流，请勿用于任何商业用途！感谢大家！<br>

CloudMusic
>cloud_music.py　　网易云音乐下载1<br>
>
>>使用requests库 通过音乐id跳转到真实下载地址进行音乐下载 <br>
>>只能用于未登录用户有权限下载的歌曲 <br>
>>模块依赖：requests　　BeautifulSoup <br>
>><br>
>
>selenium_to_cloud_music.py　　网易云音乐下载2 <br>
>
>>使用selenium模拟浏览器请求页面与用户点击，通过浏览器返回的数据提取下载链接进行下载 <br>
>>只要能够在网页上正常播放的歌曲都可以进行下载 <br>
>>模块依赖：selenium　　requests <br>
>>外部依赖：chromedriver.exe <br>
>
bilibili
>bilibili.py　　bilibili视频下载<br>
>
>>使用selenium模拟浏览器请求页面与用户点击，通过浏览器返回的数据提取下载链接进行下载 <br>
>>能够获取用户上传的视频<br>
>>模块依赖：selenium　　requests　　BeautifulSoup<br>
>>外部依赖：chromedriver.exe <br>
>>
>
>bilibili_bangumi.py　　bilibili番剧下载<br>
>
>>原理同上
>>如果视频进行分片传输,则只能获取第一个片段
>>依赖同上
>>
>
>danmaku_download.py　　bilibili番剧弹幕下载
>
>>使用selenium模拟浏览器请求页面,使用pyautogui控制鼠标点击相应Windows窗口事件,完成自动化下载 <br>
>>能够获取番剧的弹幕文件(以xml的格式) <br>
>>模块依赖：selenium　　pyautogui<br>
>>外部依赖：chromedriver.exe <br>
>>注：要将xml转化为ass(字幕格式)的文件时,可以使用　[bilibili ASS 弹幕在线转换](https://tiansh.github.io/us-danmaku/bilibili/)
>>
