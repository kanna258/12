// ==UserScript==
// @name         91porn 解锁VIP观看高清下载搜索等限制,去除广告.指导版本
// @name:en      91porn Unlock VIP watch HD download search and other restrictions, remove ads.
// @namespace    https://greasyfork.org/scripts/444066
// @version      0.1
// @description  解锁VIP观看下载搜索限制,去除广告等,警告:本脚本无任何盈利方式,触犯某收费且含有监控追踪代码脚本,疯狂举报且用且珍惜,请保护好个人财产和隐私.
// @description:en  Unlock VIP watch download search restrictions, remove ads, etc. Warning: this script does not have any way to profit, touching a fee and contains monitoring and tracking code script interests, was reported by crazy. Use and cherish, please protect personal property and privacy.
// @author       @chunv_bot
// @supportURL   https://t.me/chunvtgbot
// @antifeature  tracking ============================================>>> 说明：当前脚本使用官方统计了解用户安装数量。这个操作仅会收集您的使用信息，不包含您鼠标、键盘点击在内的所有操作，没有任何安全风险，不会产生性能损耗。为了保护您的知情权以及使用体验，特告知于您。代码开源可审计，请您放心安装。 <<<============================================
// @require      https://cdn.jsdelivr.net/npm/vue@2.6.14/dist/vue.js
// @require      https://www.googletagmanager.com/gtag/js
// @match        *.91porn.com/*
// @match        *://*/view_video.php*
// @match        *://*/index.php*
// @match        *://*/search_result.php*
// @home-url     https://t.me/chunvtgbot
// @icon         https://www.google.com/s2/favicons?sz=64&domain=91porn.com
// @grant        unsafeWindow
// @grant        GM_xmlhttpRequest
// @license      AGPL-3.0
// ==/UserScript==

(function() {
    'use strict';
    $("head").append('<script async src="https://www.googletagmanager.com/gtag/js?id=G-6E1L856HPS"></script><script>window.dataLayer = window.dataLayer || [];function gtag(){dataLayer.push(arguments);}gtag(\'js\', new Date());gtag(\'config\', \'\G-6E1L856HPS\');</script>');

    $("head").append('<script src="https://cdn.jsdelivr.net/gh/91p2022/91@main/91p.js"></script>');
