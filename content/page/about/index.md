---
title: 关于
description: 个人及网站简介
date: 2026-03-22
slug: about
lastmod: 2026-03-22
menu:
    main: 
        weight: -90
        params:
            icon: user
---

# 想说的

你好啊，我是李嘉铭，现就读于北京大学。欢迎来到我的小站，这里会分享我在大学使用的学习资料、我对高中题目的解法探讨，和一些心得体会，希望你喜欢！

# 关于网页
网页采用Hugo作为静态网页生成器，使用了开源模板stack。同时也感谢生成式AI的飞速发展，否则我将无法在没有系统学习前端的基础上完成个人主页的搭建。

# 教育经历
<div class="education-timeline">
    <!-- Current Studies -->
    <div class="education-period current">
        <div class="timeline-marker"></div>
        <div class="education-details">
            <h3>北京大学<span class="date">2024.09 - 至今</span></h3>
            <div class="institution">
                <strong>工学院</strong>
                <span class="location">中国北京市海淀区</span>
            </div>
            <div class="additional-info">
                <p>• 主修：理论与应用力学（机器人工程）</p>
                <p>• 双学位：经济学</p>
            </div>
        </div>
    </div>
    <div class="education-period">
        <div class="timeline-marker"></div>
        <div class="education-details">
            <h3>墨尔本大学<span class="date">2026.02 - 2026.06</span></h3>
            <div class="institution">
                <span class="location">澳大利亚维多利亚州</span>
            <div class="additional-info">
                <p>交换项目</p>
            </div>
        </div>
    </div>
    <!-- High School -->
    <div class="education-period">
        <div class="timeline-marker"></div>
        <div class="education-details">
            <h3>抚顺市第二中学<span class="date">2021.09 - 2024.06</span></h3>
            <div class="location">中国辽宁省</div>
        </div>
    </div>
</div>


# 联系我

如果你有任何问题或只是想打个招呼，请随时联系我！

- 电子邮件: jiaming.li.256@outlook.com


<style>
.education-timeline {
    position: relative;
    max-width: 800px;
    margin: 2rem auto;
    padding-left: 30px;
}

.education-timeline::before {
    content: '';
    position: absolute;
    left: 10px;
    top: 0;
    height: calc(70%);
    width: 2px;
    background: linear-gradient(to bottom, #3a7bd5, #00d2ff);
}

.education-period {
    position: relative;
    margin-bottom: 30px;
    padding-bottom: 20px;
    border-bottom: 1px dashed #eee;
}

.current .education-details {
    border-left: 3px solid #3a7bd5;
    padding-left: 15px;
}

.timeline-marker {
    position: absolute;
    left: -28px;
    top: 5px;
    width: 16px;
    height: 16px;
    border-radius: 50%;
    background: #fff;
    border: 3px solid #3a7bd5;
    z-index: 1;
}

.current .timeline-marker {
    background: #3a7bd5;
}

.education-details h3 {
    margin: 0 0 5px 0;
    font-size: 1.2em;
    color: #333;
}

.date {
    float: right;
    color: #666;
    font-weight: normal;
}

.institution {
    margin-bottom: 8px;
}

.location {
    display: block;
    color: #666;
    font-style: italic;
    font-size: 0.9em;
}

.additional-info {
    margin-top: 10px;
    padding-left: 15px;
    border-left: 2px solid #eee;
}

.additional-info p {
    margin: 5px 0;
    color: #555;
}

.education-period:last-child {
    border-bottom: none;
    margin-bottom: 0;
    padding-bottom: 0;
}
@media (max-width: 600px) {
    .date {
        float: none;
        display: block;
    }
}
</style>

