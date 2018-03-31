# pdf2word
批量PDF转化为Word
# 使用说明
1.clone或下载项目到本地
git clone git@github.com:hilln/pdf2word.git

2.修改config.cfg文件，指定存放pdf和word文件的文件夹，以及同时工作的进程数
 我的设置：（最好放在同一目录下）
 pdf_folder=/work/pdf2word
 word_folder=/work/pdf2word
 max_worker=2//最大进程数
3.执行python pdf2word.py

# 特别注意
  1.部分PDF转换Word不成功是因为缺少字体的原因，需要下载相应的字体包放到相应位置
  2.PDF中的图片不能转换
 
