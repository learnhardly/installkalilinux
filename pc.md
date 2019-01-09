<div id="article_content" class="article_content clearfix csdn-tracking-statistics" data-pid="blog" data-mod="popu_307" data-dsm="post">
								            <link rel="stylesheet" href="https://csdnimg.cn/release/phoenix/template/css/ck_htmledit_views-5edb848729.css">
						<div class="htmledit_views" id="content_views">
                
<p><span style="font-family:'宋体';">下面给大家讲解一下如何在我们的物理机上安装</span>Kali<span style="font-family:'宋体';">系统，废话不多说，下面直接开始：</span></p>
<p><span style="font-size:24px;"><strong><span style="font-family:'宋体';color:#CC0000;">一：准备材料</span></strong></span></p>
<p>1）&nbsp;Universal_USB_Installe <span style="font-family:'宋体';">系统镜像烧录工具</span></p>
<p><span style="font-family:'宋体';">&nbsp;&nbsp;&nbsp; 下载地址：</span>https://universal-usb-installer.en.softonic.com/</p>
<p>2）&nbsp;Kali<span style="font-family:'宋体';">系统</span></p>
<p><span style="font-family:'宋体';">&nbsp;&nbsp;&nbsp; 下载地址：</span>https://www.kali.org/downloads/</p>
<p>3）&nbsp;4G<span style="font-family:'宋体';">以上</span><span style="font-family:Calibri;">U</span><span style="font-family:'宋体';">盘一个</span></p>
<p>&nbsp;</p>
<p><span style="font-size:24px;color:#990000;"><strong>二、<span style="font-family:'宋体';">制作</span>U<span style="font-family:'宋体';">盘引导启动盘</span></strong></span></p>
<p><span style="font-family:'宋体';">提醒：</span> <span style="font-family:'宋体';">在制作</span> U<span style="font-family:'宋体';">盘启动器时，请务必先将</span><span style="font-family:Calibri;">U</span><span style="font-family:'宋体';">盘中的文件备份好，因为在制作启动盘时，制作工具会将</span><span style="font-family:Calibri;">U</span><span style="font-family:'宋体';">盘进行格式化！所以务必备份文件，切记！切记！</span></p>
<p><span style="font-family:'宋体';">好，下面开始制作启动盘：</span></p>
<p><span style="font-family:'宋体';">运行</span> Universal_USB_Installe <span style="font-family:'宋体';">
工具：</span></p>
<p>setp 1<span style="font-family:'宋体';">：选择 </span><span style="font-family:Calibri;">Kali Linux &nbsp;setp 2</span><span style="font-family:'宋体';">：选择下载好的</span><span style="font-family:Calibri;">Kali</span><span style="font-family:'宋体';">系统镜像包
</span><span style="font-family:Calibri;">setp 3</span><span style="font-family:'宋体';">：选择要制作的</span><span style="font-family:Calibri;">U</span><span style="font-family:'宋体';">盘，具体如下：</span></p>
<img src="https://img-blog.csdn.net/20180109110801422?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcWludGFpd3U=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" alt=""><br><p><span style="font-family:'宋体';"></span></p>
<p><span style="font-family:'宋体';">此时系统弹出一个制作复查信息，如果确定无误，点击</span>‘是’即可开始制作：</p>
<p><img src="https://img-blog.csdn.net/20180109110918733?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcWludGFpd3U=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" alt=""></p>
<p></p>
<p><span style="font-family:'宋体';">制作的时间长短取决于</span>U<span style="font-family:'宋体';">盘的性能，至此</span><span style="font-family:Calibri;">U</span><span style="font-family:'宋体';">盘启动器制作完成！</span></p>
<p>&nbsp;</p>
<p><span style="font-size:24px;"><strong><span style="color:#CC0000;">二、<span style="font-family:'宋体';">开始安装系统</span></span></strong></span></p>
<p><span style="font-family:'宋体';">在正式安装系统时，你需要将系统的启动项设置为</span>U<span style="font-family:'宋体';">盘启动（</span><span style="font-family:Calibri;">U</span><span style="font-family:'宋体';">盘第一启动项），不同的电脑设置的方法不一样，有的是</span><span style="font-family:Calibri;">DEL</span><span style="font-family:'宋体';">、</span><span style="font-family:Calibri;">F2</span><span style="font-family:'宋体';">、</span><span style="font-family:Calibri;">ESC</span><span style="font-family:'宋体';">键进入</span><span style="font-family:Calibri;">BIOS</span><span style="font-family:'宋体';">设置，具体方法请自行百度。</span></p>
<p><span style="font-family:'宋体';">此时将</span>U<span style="font-family:'宋体';">盘插入</span><span style="font-family:Calibri;">USB</span><span style="font-family:'宋体';">口中（建议插入置后置的</span><span style="font-family:Calibri;">USB</span><span style="font-family:'宋体';">口中），然后重启电脑，如果一切正常，系统会进入到以下界面：</span></p>
<img src="https://img-blog.csdn.net/20180109111041661?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcWludGFpd3U=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" alt=""><p></p>
<p><span style="font-family:'宋体';">此时我们选择</span> ‘<span style="font-family:Calibri;">Graphical install</span><span style="font-family:'宋体';">’项进行安装，进入下一步：</span></p>
<p><span style="font-family:'宋体';">（说明：</span>‘<span style="font-family:Calibri;">Install</span><span style="font-family:'宋体';">’安装的是无界面的</span><span style="font-family:Calibri;">Kali</span><span style="font-family:'宋体';">系统，而‘</span><span style="font-family:Calibri;">Graphical
 install</span><span style="font-family:'宋体';">’安装的是带</span><span style="font-family:Calibri;">UI</span><span style="font-family:'宋体';">界面的系统）</span></p>
<p><span style="font-family:'宋体';">根据自己的习惯选择合适的语言，这里选择</span>‘中文（简体）’：</p>
<img src="https://img-blog.csdn.net/20180109111144050?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcWludGFpd3U=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" alt=""><p></p>
<p><span style="font-family:'宋体';">选择</span>‘是’，确定以该语言就行安装，进入下一步：</p>
<img src="https://img-blog.csdn.net/20180109111217185?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcWludGFpd3U=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" alt=""><br><p></p>
<p><span style="font-family:'宋体';">根据情况选择</span>‘地方区域’配置，这里选择‘中国’，下一步：</p>
<p><img src="https://img-blog.csdn.net/20180109111305167?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcWludGFpd3U=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" alt=""><br></p>
<p><span style="font-family:'宋体';">选择</span>‘配置键盘’为汉语，下一步：</p>
<img src="https://img-blog.csdn.net/20180109111416427?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcWludGFpd3U=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" alt=""><br><p><span style="font-family:'宋体';"></span></p>
<p><span style="font-family:'宋体';">此时，程序会探测并挂载光盘，</span><strong><span><span style="font-family:'宋体';">如果提示没有检测到挂载光盘，这时只需将</span>U<span style="font-family:'宋体';">盘拔下再重新插上，再次执行检测即可！如果不行多重复操作几次或更换</span><span style="font-family:Calibri;">USB</span><span style="font-family:'宋体';">接口测试</span></span></strong><span style="font-family:'宋体';">！</span></p>
<img src="https://img-blog.csdn.net/20180109111457383?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcWludGFpd3U=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" alt=""><br><p><span style="font-family:'宋体';"></span></p>
<p><span style="font-family:'宋体';">正常运行，并开始安装：</span></p>
<img src="https://img-blog.csdn.net/20180109111537622?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcWludGFpd3U=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" alt=""><br><p><span style="font-family:'宋体';"></span></p>
<p><span style="font-family:'宋体';">接下来，自行根据安装提示安装基本上就可以完成了，如果不清楚的可直接</span>‘下一步’或‘继续’跳过，即可完成<span style="font-family:Calibri;">Kali</span><span style="font-family:'宋体';">系统的安装。</span></p>
<p><span style="font-family:'宋体';">系统安装成功后，电脑会重启，此时需要先将</span>U<span style="font-family:'宋体';">盘拔下，才能进入刚才安装好的系统，最后附上一张安装成功后的图片：</span></p>
<p><span style="font-family:'宋体';"><br></span></p>
<p><span style="font-family:'宋体';"><br></span></p>
<p><span style="font-family:'宋体';"><img src="https://img-blog.csdn.net/20180109112112071?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcWludGFpd3U=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast" alt=""><br></span></p>
<p><span style="font-family:'宋体';">至此Kali系统安装完成！！<br></span></p>
            </div>
                </div>
