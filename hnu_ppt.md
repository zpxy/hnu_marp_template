---
# 一定要开启marp的html支持
# 可以生成网页和pdf
# 生成的pptx不可修改
marp: true
size: 16:9
theme: default
paginate: true
style: |
    header {
      height: 60px;
      color: rgb(60, 112, 198);
      font-weight: bold;
      font-size: 36px;
      top: 1%;
      left: 5%;
    }
    
header: ""
# todo 更改学院信息
footer: <span style="font-size:26px;text-align:center">信息与通信工程学院</span>  
# 这里是右上角logo 
backgroundImage: url(./img/HNU.png)
backgroundSize: 18%
backgroundPosition: top 1% right 1%

---
<!-- 封面设置 -->
<style scoped>
    section {
       text-align: center;
       font-family: '仿宋';
    }
    .hnu_img {
        /* border: 5px solid; */
        padding-top:120px;
        padding-bottom:10px;
    }
    h1{
      color: #eef;
       
      margin-bottom: 20px;
      /* border: 5px solid  */
    }
    .info {
        margin-top:50px;
        text-align:left;
        padding-left:40%;
    }
</style>
<!--
_backgroundImage: url("./img/bg1.jpg")
_paginate: false 
_backgroundSize: 100%
_backgroundPosition: top 70% 
_header: ""
_footer: ""  
-->

<div class='hnu_img'>

![img w:400](./img/HNU.png)

</div>
<!-- todo :不要删除下面这行空格 ：在#号之后填入你的题目 -->

# 海南大学<br/>模板

<div class="info"> 

<!-- todo :不要删除上面这行空格 ：在合适的地方填入你的信息 -->
**答辩人：张三** 
**导&emsp;师：罗辑教授**
**专&emsp;业：宇宙法学**
**&emsp;2024 年 5 月**

</div>

---
<!-- 目录页 -->
<!-- 使用_headers 指定页眉的那内容-->
<!-- 
_header: "Contents" 
-->
<style scoped>
  .col {
    display: grid;
    grid-template-columns: 25% 1fr;
  }
  .col_1 {
    border-right-style:dotted;
    border-right-width:5px;
  }
  .col_1 .p1 {
    height:100%;
    font-size:72px;
    /* font-weight:bold; */
    font-family:'方正小标宋简体';
    text-align:center;
    padding-top:25%;
  }
  .col_2 {
    /* background: pink; */
    padding-left:40px;
  }
</style>
<div class="col">
<div class='col_1'>
    <p class='p1'>目<br>录</p>
</div>
<div class='col_2'> 
<br/>

<!-- todo :请你修改成自己的目录-->
1. <big>研究背景与意义</big>
2. <big>研究方案与实现</big>
3. <big>研究结论</big>
4. <big>工作总结与展望</big>

<br/>
</div>
</div>

---
<!--
_header: "一、研究背景和意义"
-->




<!-- 使用---语法分割一页ppt，注意之前要空一行 -->

---
<!--
_header: "二、研究方案与实现"
-->


---
<!--
_header: "三、研究结论"
-->



---
<!--
_header: "四、工作总结与展望"
-->



---
<!-- 感谢页 -->
<!--
_header: ""
_footer: ""  
_backgroundImage: ""
_paginate: false 
_backgroundSize: 100%
-->
<style scoped>
    section {
       text-align: center;
      
       font-family: 仿宋;
       /* background-color: #66CCFF; */
    }
</style>

![img w:400](./img/HNU.png)
<!-- Thank You! -->
<p style="font-size:80px;">恳请各位老师批评指导!</p>
<p style="font-size:50px;">张三</p>
<p style="font-size:40px;">2024.05</p>
