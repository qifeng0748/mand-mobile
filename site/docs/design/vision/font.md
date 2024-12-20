---
title: 字体
---
字体是体系化界面设计中最基本的构成之一，「好用」和「美观」的字体设计原则。

<div class="doc-font-list doc-font-area">
  <div class="doc-font-item">
    <div class="doc-font-title">
      iOS&nbsp;&nbsp;系统
    </div>
    <div class="doc-font-text">
      中文&nbsp;&nbsp;&nbsp;&nbsp;PingFang  SC 苹方
    </div>
    <div class="doc-font-text">
      数字&nbsp;&nbsp;&nbsp;&nbsp;DIN Pro-Medium
    </div>
  </div>
  <div class="doc-font-item">
    <div class="doc-font-title">
      Android 系统
    </div>
    <div class="doc-font-text">
      中文&nbsp;&nbsp;&nbsp;&nbsp;Noto Sans S Chinese  思源
    </div>
    <div class="doc-font-text">
      数字&nbsp;&nbsp;&nbsp;&nbsp;Helvetica/DIN Pro-Medium
    </div>
  </div>
  <div class="doc-font-item">
    <div class="doc-font-title">
      H5
    </div>
    <div class="doc-font-text">
      中文&nbsp;&nbsp;&nbsp;&nbsp;根据系统
    </div>
    <div class="doc-font-text">
      数字&nbsp;&nbsp;&nbsp;&nbsp;DIN Pro-Medium
    </div>
  </div>
</div>
<div class="doc-font-list doc-font-area">
  <div class="doc-font-item">
    <div class="doc-font-title">
      品牌字体
    </div>
    <div class="doc-font-typeface">
      <img src="https://pt-starimg.didistatic.com/static/starimg/img/0gWbj5fuLN1643183908647.png" class="font-typeface-img">
    </div>
  </div>
</div>

<style>
.doc-content-paragraph h4{margin-top:60px}
.doc-font-typeface{padding:35px 35px 15px 35px}
.doc-font-area{margin-top:40px}
.doc-font-list{display:-webkit-box;display:-ms-flexbox;display:flex}
.doc-font-item{-webkit-box-flex:1;-ms-flex:1;flex:1;margin-right:40px;padding-bottom:20px;border:solid 1px #E2E4EA}
.doc-font-item:last-of-type{margin-right:0}
.doc-font-title{padding:12px 24px;background:#F4F5F7;font-size:14px;color:#111A34;font-weight:500}
.doc-font-text{float:left;width:100%;margin-top:12px;padding:0 24px;font-size:14px;color:#41485D;-webkit-box-sizing:border-box;box-sizing:border-box}
.doc-font-text span.l{float:left}
.doc-font-text span.r{float:right}
.font-weight-item{width:220px;height:220px;margin-right:20px}
.font-size-img{max-width:80%!important;margin-top:32px!important}
.font-weight-img{width:100%;height:100%;background-size:100% 100%;}
.font-weight-list{margin-top:32px}
.font-hight-img{width:1191px;height:409px;background-size:cover;margin-top:32px;margin-bottom:24px;max-width:100%}
@media (max-width:750px){.doc-font-list{-webkit-box-orient:vertical;-webkit-box-direction:normal;-ms-flex-direction:column;flex-direction:column}
.doc-font-item{max-width:none!important;margin-right:0;margin-bottom:20px}
.font-size-img{max-width:100%!important}
.font-hight-img{height:280px}
}
.font-typeface-img{width:100%;height:100%;background-size:100% 100%;}
</style>

#### 字号

字体的使用注意中文和英文的使用，金融类的产品数字均为页面的重要信息。<br>
中文字体建议最大字号是60Px，最小为24px；英文字体DIN Pro  Medium（在页面强突出金额时使用）建议最大字号120px。其中字号大小均为偶数（4的倍数最佳），以保障所有开发场景下为整数的单位。特殊场景的需要，字号标准可做相应调整。<br>
<img src="https://pt-starimg.didistatic.com/static/starimg/img/R1ke1asaDm1545968523580.jpg" class="font-size-img">

#### 字重

多数情况下，中文只出现 regular 以及 medium 的两种字体重量，数字字体DIN Pro只出现medium字重。

<div class="doc-font-list font-weight-list">
  <div class="font-weight-item">
    <img src="https://pt-starimg.didistatic.com/static/starimg/img/KRGD1SwMaB1643185507535.png" class="font-weight-img">
  </div>
  <div class="font-weight-item">
    <img src="https://pt-starimg.didistatic.com/static/starimg/img/NOKvBvStRy1643185339122.png" class="font-weight-img">
  </div>
  <div class="font-weight-item">
    <img src="https://pt-starimg.didistatic.com/static/starimg/img/1Q1n66pE6x1643185338853.png" class="font-weight-img">
  </div>
</div>

#### 行高

在当字号越大的时候，行高就会越大，在大号文字的展示上信息的连贯明显得出现割裂。因此建议不同字号之间的间距都保持相同，通过逻辑得到这样一个公式：「 行高 = 字号 + n 」 N为4的倍数，推荐为8。
<img src="https://pt-starimg.didistatic.com/static/starimg/img/bes4GgXj3D1643358533063.png" class="font-hight-img">
