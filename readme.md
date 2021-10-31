### 使用教程

1. 运行软件前先打开目录下 conf.ini 文件按照要求进行配置

  批量下载可直接修改配置文件，单一视频下载请直接打开主程序粘贴视频分享链接即可

2. 本项目制作了pip包，可以输入 ``` pip install TikTokDownload==1.2.3 ```安装

   **包使用方法：**

   ```python
   #example.py
   #用户主页批量下载
   import TikTokMulti as MTK
   
   MTK.TikTok()
   
   #单视频下载
   import TikTokDownload as TK
   
   TK.video_download(TK.main())
   ```

   ***example.py需确保TikTokMulti.py与TikTokDownload.py两个文件都在相同目录中***