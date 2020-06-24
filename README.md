<!DOCTYPE html>
<html lang="en" class=""><head>
    <meta charset="UTF-8">
    <title>简历生成器</title>
    <link rel="stylesheet" href="static/css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/remodal/1.1.0/remodal.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/remodal/1.1.0/remodal-default-theme.min.css">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/remodal/1.1.0/remodal.min.js"></script>
    <script src="static/js/script.js"></script>
</head>

<body style="padding-right: 0px;">
    <div class="container" id="cv">
        <div class="side">
            <div class="me">
                <div class="portrait"></div>
                
                <h1 id="username" contenteditable="true"></h1>
                <h4 id="persona-tag" contenteditable="true"></h4>
            </div>
            <div class="profile info-unit">
                <h2 class="info-header"><i class="iconfont icon-person"></i> <span class="info-title" contenteditable="true">基本信息</span><span class="item-add" style="visibility: hidden;"><i class="iconfont icon-playlistadd"></i></span><span class="unit-remove" style="visibility: hidden;"><i class="iconfont icon-delete"></i></span></h2>
                <hr>
                <ul class="info-list">
                    <li>
                        <label class="left-label" contenteditable="true">姓名</label><span class="label-value" contenteditable="true">刘一博</span><span class="item-remove" style="visibility: hidden;"><i class="iconfont icon-delete"></i></span></li>
                    <li>
                        <label class="left-label" contenteditable="true">学历</label><span class="label-value" contenteditable="true">大专</span><span class="item-remove" style="visibility: hidden;"><i class="iconfont icon-delete"></i></span></li>
                    <li>
                        <label class="left-label" contenteditable="true">毕业院校</label><span class="label-value" contenteditable="true">福州职业技术学院</span><span class="item-remove" style="visibility: hidden;"><i class="iconfont icon-delete"></i></span></li>
                    <li>
                        <label class="left-label" contenteditable="true">毕业年份</label><span class="label-value" contenteditable="true">2020</span><span class="item-remove" style="visibility: hidden;"><i class="iconfont icon-delete"></i></span></li>
                </ul>
            </div>
            <div class="contact info-unit">
                <h2 class="info-header"><i class="iconfont icon-call"></i> <span class="info-title" contenteditable="true">联系方式</span><span class="item-add" style="visibility: hidden;"><i class="iconfont icon-playlistadd"></i></span><span class="unit-remove" style="visibility: hidden;"><i class="iconfont icon-delete"></i></span></h2>
                <hr>
                <ul class="info-list">
                    <li>
                        <label class="left-label" contenteditable="true">手机</label><span class="label-value" contenteditable="true">17326587603</span><span class="item-remove" style="visibility: hidden;"><i class="iconfont icon-delete"></i></span></li>
                    <li>
                        <label class="left-label" contenteditable="true">邮箱</label><span class="label-value" contenteditable="true">imliuyibo@163.com</span><span class="item-remove" style="visibility: hidden;"><i class="iconfont icon-delete"></i></span></li>
                    
                    
                </ul>
            </div>
            <div class="skill info-unit">
                <h2 class="info-header"><i class="iconfont icon-star"></i> <span class="info-title" contenteditable="true">技能点</span><span class="item-add" style="visibility: hidden;"><i class="iconfont icon-playlistadd"></i></span><span class="unit-remove" style="visibility: hidden;"><i class="iconfont icon-delete"></i></span></h2>
                <hr>
                <ul class="progress-list">
                    <li>
                        <label class="left-label" contenteditable="true">网络知识</label>
                        <progress value="83.59374999999999" max="100"></progress>
                    <span class="item-remove" style="visibility: hidden;"><i class="iconfont icon-delete"></i></span></li>
                    <li>
                        <label class="left-label" contenteditable="true">office</label>
                        <progress value="70" max="100"></progress>
                    <span class="item-remove" style="visibility: hidden;"><i class="iconfont icon-delete"></i></span></li>
                    <li>
                        <label class="left-label" contenteditable="true">外语技能(英语)</label>
                        <progress value="39.0625" max="100"></progress>
                    <span class="item-remove" style="visibility: hidden;"><i class="iconfont icon-delete"></i></span></li>
                    
                </ul>
            </div>
            

            <div class="code info-unit">
                <h2 class="info-header"><i class="iconfont icon-weixin"></i> <span class="info-title" contenteditable="true">个人微信</span><span class="unit-remove" style="visibility: hidden;"><i class="iconfont icon-delete"></i></span></h2>
                <hr>
                <div class="weixin">
                    <img src="static/image/weixin.png" alt="">

                </div>
            </div>
            
        </div>
        <div class="main">
            <div class="education info-unit right-list">
                <h2 class="info-header"><i class="iconfont icon-education"></i> <span class="info-title" contenteditable="true">教育经历</span><span class="item-add" style="visibility: hidden;"><i class="iconfont icon-playlistadd"></i></span><span class="unit-remove" style="visibility: hidden;"><i class="iconfont icon-delete"></i></span></h2>
                <hr>
                <ul class="experience-list">
                    <li>
                        <h3 contenteditable="true">福州职业技术学院 - 网络工程专业（大专）2017-2020</h3>
                        
                    <span class="item-remove" style="visibility: hidden;"><i class="iconfont icon-delete"></i></span></li>
                </ul>
            </div>
            <div class="work info-unit right-list">
                <h2 class="info-header"><i class="iconfont icon-work"></i> <span class="info-title" contenteditable="true">工作经历</span><span class="item-add" style="visibility: hidden;"><i class="iconfont icon-playlistadd"></i></span><span class="unit-remove" style="visibility: hidden;"><i class="iconfont icon-delete"></i></span></h2>
                <hr>
                <ul class="experience-list">
                    <li>
                        <h3 contenteditable="true">福建德源信息技术服务有限公司(实习)</h3>
                        <p contenteditable="true">负责H3C售后网络硬件的维护、设备初始化工作。</p><div>负责客户户管理及网络使用维护，有效的解决网络遇到的疑难问题。
                        </div><div>负责客户售后服务支持,服务器、网络硬件设备的维护、软硬件技术支持，做好计算机网络系统运行情况日常记录，保证系统的可靠性。</div><div>及时解决客户使用网络和计算机方面的疑难问题。<br></div><div><br></div><p></p>





                    <span class="item-remove" style="visibility: hidden;"><i class="iconfont icon-delete"></i></span></li>
                    
                </ul>
            </div>
            <div class="project info-unit right-list">
                <h2 class="info-header"><i class="iconfont icon-project"></i> <span class="info-title" contenteditable="true">个人项目</span><span class="item-add" style="visibility: hidden;"><i class="iconfont icon-playlistadd"></i></span><span class="unit-remove" style="visibility: hidden;"><i class="iconfont icon-delete"></i></span></h2>
                <hr>
                <ul class="experience-list">
                    <li>
                        <h3 contenteditable="true">创客工作室(负责人、部长)</h3>
                        <p contenteditable="true"><div>[曾在创客工作室担任工作室负责人、运维部部长]</div><div>[组织工作室制定中秋节活动计划，协调前期分工及准备工作，实时跟进活动布置情况，根据突发问题调整任务，确保活动的顺利推进及开展]</div><div>[协完成策划书编写任务，协助制作活动海报，并进行各种原料采购，保证活动顺利进行]</div>
                        </p>
                    <span class="item-remove" style="visibility: hidden;"><i class="iconfont icon-delete"></i></span></li>
                    <li>
                        <h3 contenteditable="true">二级学院微信公众号运营</h3>
                        <p contenteditable="true"><div>[组织二级学院制定微信公众号线上活动计划，协调前期分工及准备工作，实时跟进线上活动情况，根据突发问题调整任务，确保活动的顺利推进及开展]</div><div>[协完成学校布置的线上任务，协助管理并统计活动物资，并进行各种原料采购，保证微信公众号顺利运行]</div><div>[负责工作室微信公众号运维人员培训工作]</div><div>[负责工作室微信公众号改版、推文撰写、审核、发布]</div></p>
                    <span class="item-remove" style="visibility: hidden;"><i class="iconfont icon-delete"></i></span></li>
                    
                    
                </ul>
            </div>
            <div class="trophy info-unit">
                <h2 class="info-header"><i class="iconfont icon-trophy"></i> <span class="info-title" contenteditable="true">专业技能</span><span class="item-add" style="visibility: hidden;"><i class="iconfont icon-playlistadd"></i></span><span class="unit-remove" style="visibility: hidden;"><i class="iconfont icon-delete"></i></span></h2>
                <hr>
                <ul class="experience-list">
                    <li>
                        <h3 contenteditable="true">熟练掌握H3C、CISCO等厂商设备命令</h3>
                        
                    <span class="item-remove" style="visibility: hidden;"><i class="iconfont icon-delete"></i></span></li> 
                    <li>
                        <h3 contenteditable="true">熟练使用office、PS等办公、绘图、视频编辑等软件</h3>
                        
                    <span class="item-remove" style="visibility: hidden;"><i class="iconfont icon-delete"></i></span></li> 
                    <li>
                        <h3 contenteditable="true">熟练运用各种微信公众号编辑软件,可独立使用创客贴、搞定设计等作图软件制作物料宣传图</h3>
                        
                    <span class="item-remove" style="visibility: hidden;"><i class="iconfont icon-delete"></i></span></li>                     
            </ul></div>
            <div class="aboutme info-unit right-paragraph">
                <h2 class="info-header"><i class="iconfont icon-flower"></i> <span class="info-title" contenteditable="true">技能/证书及其他</span><span class="unit-remove" style="visibility: hidden;"><i class="iconfont icon-delete"></i></span></h2>
                <hr>
<p contenteditable="true">
                    证书/执照： H3CNE
                </p>
<p contenteditable="true">
                    技能： MOS Office
                </p>
<p contenteditable="true">
                    活动项目： 学院公众号(运营)
                </p>
<p contenteditable="true">
                    兴趣爱好： 游戏，听歌，跑步
                </p>
                <p contenteditable="true"></p>
            </div>
        </div>
    </div>



<div class="remodal-overlay remodal-is-closed" style="display: none;"></div><div class="remodal-wrapper remodal-is-closed" style="display: none;"><div class="remodal remodal-img remodal-is-initialized remodal-is-closed" data-remodal-id="portrait-modal" tabindex="-1">
                    <h3 contenteditable="true">请输入图片URL地址：</h3>
                    <br>
                    <input type="text" id="avatar-url">
                    <button data-remodal-action="confirm" class="remodal-confirm">确定</button>
                </div></div><div class="remodal-wrapper remodal-is-closed" style="display: none;"><div class="remodal remodal-img remodal-is-initialized remodal-is-closed" data-remodal-id="weixin-modal" tabindex="-1">
                <h3 contenteditable="true">请输入图片URL地址：</h3>
                <br>
                <input type="text" id="weixin-url">
                <button data-remodal-action="confirm" class="remodal-confirm">确定</button>
            </div></div></body></html>
    </div>
</body>

</html>
