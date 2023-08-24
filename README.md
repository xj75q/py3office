
### 【项目缘由】
由于wps和office 的很多功能都收费，所以就在前几年写了这些脚本，现在开源出来给需要的人使用
- pdf_combine.py 文件是合并pdf使用的，需要打印资料的时候可以用此合并
- ppt2word.py 文件是提取ppt当中文字的。当ppt中的内容需要整理到自己的电子笔记中，可使用此脚本
- full_ts2mp4.py 文件是将下载的ts视频整合成一个mp4文件的，可用于视频流的转换

### 【环境准备】
mkvirtualenv py3office
workon py3office
pip install -r requirements.txt

### 【使用命令】
python pdf_combine.py --help  可查看输入参数
python pdf_combine.py -i "G:\\小说pdf_转换前\\" -o "G:\\小说pdf_转换后\\"  


**注：在win上使用，里面的路径为“\\”(双斜杠)**

###  【其他】
使用full_ts2mp4.py 需在win上安装[ffmpeg](https://ffmpeg.org/) ，将py文件中的__init__里的ffmpeg路径修改掉
