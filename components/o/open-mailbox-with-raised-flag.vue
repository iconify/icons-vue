<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#ilEfLHN)" class="rznriwbau"/><path fill="url(#iPb3uQc)" class="rznriwbau"/><path fill="url(#iWP5jgC)" class="rznriwbau"/><g filter="url(#iPc8Yid)"><path fill="url(#iOEomYz)" class="bjea3_5ts"/><path fill="url(#iMS1Cie)" class="bjea3_5ts"/></g><g filter="url(#i9gNN0s)"><path class="sjagd30ip"/><path stroke="url(#iKkNrac)" class="qleet2bok"/></g><g filter="url(#iwlanVc)"><ellipse class="hdu1ly20u"/></g><g filter="url(#i3l7gic)"><path fill="url(#i2DP0Db)" class="ubx36-iyc"/></g><path fill="url(#itpimbn)" class="q53k2_j6z"/><g filter="url(#iiKhL7J)"><path fill="url(#i4dY7te)" class="b_fteneea"/></g><path fill="url(#iy4cElb)" class="nf25b1bta"/><path fill="url(#iNrOEGh)" class="nf25b1bta"/><path fill="url(#i0dGONG)" class="nf25b1bta"/><g filter="url(#iWajfDb)"><rect transform="rotate(-90 18.973 11.908)" class="uk-817bee"/></g><circle fill="url(#iE7a7Ge)" transform="matrix(0 -1 -1 0 19.21 13.586)" class="g4va65bde"/><circle fill="url(#ivfSMJd)" transform="matrix(0 -1 -1 0 19.21 13.586)" class="g4va65bde"/><circle fill="url(#ilgjLtc)" transform="matrix(0 -1 -1 0 19.21 13.586)" class="g4va65bde"/><path fill="url(#iAPLsrd)" class="j-p2h4biw"/><path fill="url(#iC8CHIO)" class="j-p2h4biw"/><path fill="url(#ilYLRQJ)" class="j-p2h4biw"/><g filter="url(#inJQJce)"><path fill="url(#iNFOlpc)" class="emvy77bhi"/></g><path fill="url(#iJ0YCfe)" class="bi0_alb4a"/><path fill="url(#iGcMgrp)" class="bi0_alb4a"/><g filter="url(#ij7Viyd)"><path fill="url(#i2cJWlc)" class="q1q7fsbcf"/><path fill="url(#iZNpfEc)" class="q1q7fsbcf"/></g></g><defs><linearGradient id="ilEfLHN" x1="16.822" x2="13.186" y1="29.879" y2="29.879" gradientUnits="userSpaceOnUse"><stop class="q2664bbii"/><stop offset=".42" class="v3rncsbye"/><stop offset=".774" class="gxbwcacfp"/></linearGradient><linearGradient id="iPb3uQc" x1="18.103" x2="17.353" y1="29.879" y2="29.879" gradientUnits="userSpaceOnUse"><stop class="w8uut-baw"/><stop offset="1" class="zrqwy0bgb"/></linearGradient><linearGradient id="iOEomYz" x1="20.525" x2="20.525" y1="24.923" y2="11.242" gradientUnits="userSpaceOnUse"><stop offset=".743" class="h9ndio2-g"/><stop offset="1" class="h-91q2h_g"/></linearGradient><linearGradient id="iKkNrac" x1="17.262" x2="9.296" y1="19.63" y2="19.63" gradientUnits="userSpaceOnUse"><stop offset=".222" class="gch7t-91q"/><stop offset="1" class="ltx6labhr"/></linearGradient><linearGradient id="i2DP0Db" x1="9.538" x2="9.538" y1="10.48" y2="23.48" gradientUnits="userSpaceOnUse"><stop offset=".191" class="yqciwabyz"/><stop offset="1" class="uyqzj06di"/></linearGradient><linearGradient id="itpimbn" x1="9.926" x2="9.926" y1="10.484" y2="22.438" gradientUnits="userSpaceOnUse"><stop class="gvmd_3pyp"/><stop offset="1" class="lcf2gumwh"/></linearGradient><linearGradient id="i4dY7te" x1="22.66" x2="22.66" y1="2.971" y2="4.658" gradientUnits="userSpaceOnUse"><stop class="s2drkiaqw"/><stop offset="1" class="d16_zibtw"/></linearGradient><linearGradient id="iy4cElb" x1="18.062" x2="19.659" y1="6.221" y2="6.221" gradientUnits="userSpaceOnUse"><stop class="s9x7vp8wh"/><stop offset="1" class="hnae3ccbj"/></linearGradient><linearGradient id="iNrOEGh" x1="19.211" x2="19.211" y1="1.889" y2="3.033" gradientUnits="userSpaceOnUse"><stop class="msa_14b8b"/><stop offset="1" class="do0vnv4yn"/></linearGradient><linearGradient id="iAPLsrd" x1="7.344" x2="13.449" y1="18.709" y2="18.709" gradientUnits="userSpaceOnUse"><stop class="r_68sobta"/><stop offset=".606" class="hg9cu3bxx"/></linearGradient><linearGradient id="iC8CHIO" x1="10.472" x2="9.512" y1="15.656" y2="17.313" gradientUnits="userSpaceOnUse"><stop offset=".261" class="g_qgmwbxk"/><stop offset="1" class="zy76svb5r"/></linearGradient><linearGradient id="ilYLRQJ" x1="10.355" x2="9.73" y1="20.313" y2="19.406" gradientUnits="userSpaceOnUse"><stop class="fj6wj5fcn"/><stop offset="1" class="oo_u7tb1b"/></linearGradient><linearGradient id="iNFOlpc" x1="14.386" x2="11.043" y1="24.313" y2="19.594" gradientUnits="userSpaceOnUse"><stop class="nyu9ygbyh"/><stop offset="1" class="xy9slpbvc"/></linearGradient><linearGradient id="iJ0YCfe" x1="8.784" x2="8.992" y1="20.562" y2="20.875" gradientUnits="userSpaceOnUse"><stop offset=".212" class="mxuvzumay"/><stop offset="1" class="hgj5y-gsc"/></linearGradient><linearGradient id="iGcMgrp" x1="15.329" x2="12.106" y1="23.484" y2="23.11" gradientUnits="userSpaceOnUse"><stop offset=".214" class="iwglfk16v"/><stop offset="1" class="wpldrkowr"/></linearGradient><linearGradient id="i2cJWlc" x1="10.074" x2="14.684" y1="16.344" y2="10.219" gradientUnits="userSpaceOnUse"><stop class="ifx9_ik7t"/><stop offset="1" class="k_vw3d06s"/></linearGradient><filter id="iPc8Yid" width="24.113" height="16.283" x="4.044" y="8.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.356863 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22052"/></filter><filter id="i9gNN0s" width="12.909" height="16.398" x="3.634" y="8.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_22052" stdDeviation=".25"/></filter><filter id="iwlanVc" width="5.645" height="7.313" x="14.949" y="10.361" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_22052" stdDeviation=".625"/></filter><filter id="i3l7gic" width="10.016" height="13.5" x="4.53" y="10.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_22052" stdDeviation=".125"/></filter><filter id="iiKhL7J" width="6.58" height="4.34" x="19.57" y="2.721" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.203922 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22052"/></filter><filter id="iWajfDb" width="1.319" height="9.516" x="18.473" y="2.893" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_22052" stdDeviation=".25"/></filter><filter id="inJQJce" width="8.674" height="6.595" x="6.011" y="16.889" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.643137 0 0 0 0 0.584314 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22052"/></filter><filter id="ij7Viyd" width="8.424" height="6.095" x="6.261" y="12.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.639216 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22052"/></filter><radialGradient id="iWP5jgC" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.95639 5.62268 0 15.511 29.88)" gradientUnits="userSpaceOnUse"><stop offset=".772" class="r2t4_lbss"/><stop offset="1" class="kgtji58_q"/></radialGradient><radialGradient id="iMS1Cie" cx="0" cy="0" r="1" gradientTransform="matrix(-3.43747 -3.75003 1.58491 -1.45282 18.137 11.813)" gradientUnits="userSpaceOnUse"><stop class="oq3j5obbk"/><stop offset="1" class="e0s2rccrq"/></radialGradient><radialGradient id="i0dGONG" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.9375 .50781 0 19.565 2.033)" gradientUnits="userSpaceOnUse"><stop class="rbz9yubut"/><stop offset="1" class="hm0grp_yj"/></radialGradient><radialGradient id="iE7a7Ge" cx="0" cy="0" r="1" gradientTransform="matrix(2.69549 -1.96875 2.37524 3.25202 -.29 3.136)" gradientUnits="userSpaceOnUse"><stop offset=".104" class="uuf7d16qw"/><stop offset="1" class="zoc1v6h3d"/></radialGradient><radialGradient id="ivfSMJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.39471 -4.66751 0 2.406 -.582)" gradientUnits="userSpaceOnUse"><stop offset=".643" class="wsxh4l0ai"/><stop offset="1" class="usuc0321h"/></radialGradient><radialGradient id="ilgjLtc" cx="0" cy="0" r="1" gradientTransform="matrix(.9375 -1.75 1.31778 .70595 3.304 .98)" gradientUnits="userSpaceOnUse"><stop offset=".247" class="b7qhyuaga"/><stop offset="1" class="wzxqf6jtq"/></radialGradient><radialGradient id="iZNpfEc" cx="0" cy="0" r="1" gradientTransform="matrix(7 -1.875 4.70551 17.56721 8.23 16.094)" gradientUnits="userSpaceOnUse"><stop offset=".63" class="hpp2w7b8x"/><stop offset=".912" class="ycovydbur"/></radialGradient><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:open-mailbox-with-raised-flag" /></template>
<style>
.b_fteneea {
  d: path("M19.57 2.97h5.38c.442 0 .8.311.8.694v2.703c0 .383-.358.694-.8.694h-5.38z");
}

.b7qhyuaga {
  stop-color: var(--svg-color--d0ccda, #D0CCDA);
}

.bi0_alb4a {
  d: path("M7.209 23.484h7.225a.25.25 0 0 0 .25-.25v-5.457l-.777-.105a.22.22 0 0 0-.23 0l-7.223 4.514a.41.41 0 0 0-.193.35c0 .524.424.948.948.948");
}

.bjea3_5ts {
  d: path("M4.044 14.54a5.5 5.5 0 0 1 5.5-5.5h12.912a5.5 5.5 0 0 1 5.5 5.5v9.383a1 1 0 0 1-1 1H5.044a1 1 0 0 1-1-1z");
}

.d16_zibtw {
  stop-color: var(--svg-color--f96941, #F96941);
}

.do0vnv4yn {
  stop-color: var(--svg-color--bab9bf, #BAB9BF);
  stop-opacity: 0;
}

.e0s2rccrq {
  stop-color: var(--svg-color--4784c4, #4784C4);
  stop-opacity: 0;
}

.emvy77bhi {
  d: path("M7.209 23.484h7.225a.25.25 0 0 0 .25-.25V18.16l-.777-.488a.22.22 0 0 0-.23 0l-7.223 4.514a.41.41 0 0 0-.193.35c0 .524.424.948.948.948");
}

.fj6wj5fcn {
  stop-color: var(--svg-color--b7b1bf, #B7B1BF);
}

.ft5dv1b6b {
  fill: none;
}

.g_qgmwbxk {
  stop-color: var(--svg-color--bfb8c7, #BFB8C7);
}

.g4va65bde {
  r: 2.406px;
}

.gch7t-91q {
  stop-color: var(--svg-color--3b7bde, #3B7BDE);
}

.gvmd_3pyp {
  stop-color: var(--svg-color--4b1776, #4B1776);
}

.gxbwcacfp {
  stop-color: var(--svg-color--5e3a43, #5E3A43);
}

.h-91q2h_g {
  stop-color: var(--svg-color--5d98da, #5D98DA);
}

.h9ndio2-g {
  stop-color: var(--svg-color--5097da, #5097DA);
}

.hdu1ly20u {
  cx: 17.771px;
  cy: 14.018px;
  fill: var(--svg-color--264fc5, #264FC5);
  rx: 1.572px;
  ry: 2.406px;
}

.hg9cu3bxx {
  stop-color: var(--svg-color--e7def2, #E7DEF2);
}

.hgj5y-gsc {
  stop-color: var(--svg-color--d9d2e1, #D9D2E1);
  stop-opacity: 0;
}

.hm0grp_yj {
  stop-color: var(--svg-color--cfcbd8, #CFCBD8);
  stop-opacity: 0;
}

.hnae3ccbj {
  stop-color: var(--svg-color--a6a4af, #A6A4AF);
}

.hpp2w7b8x {
  stop-color: var(--svg-color--aca5b5, #ACA5B5);
  stop-opacity: 0;
}

.ifx9_ik7t {
  stop-color: var(--svg-color--e3dfea, #E3DFEA);
}

.iwglfk16v {
  stop-color: var(--svg-color--625c6a, #625C6A);
}

.j-p2h4biw {
  d: path("M7.26 23.484h7.174a.25.25 0 0 0 .25-.25v-7.992c0-.943-.274-1.822-.747-2.56H7.26a1 1 0 0 0-1 1v8.802a1 1 0 0 0 1 1");
}

.k_vw3d06s {
  stop-color: var(--svg-color--a5a0ad, #A5A0AD);
}

.kgtji58_q {
  stop-color: var(--svg-color--5a3a46, #5A3A46);
}

.lcf2gumwh {
  stop-color: var(--svg-color--240b46, #240B46);
}

.ltx6labhr {
  stop-color: var(--svg-color--3c84d5, #3C84D5);
  stop-opacity: 0;
}

.msa_14b8b {
  stop-color: var(--svg-color--bab9bf, #BAB9BF);
}

.mxuvzumay {
  stop-color: var(--svg-color--d9d2e1, #D9D2E1);
}

.nf25b1bta {
  d: path("M20.36 3.038a1.149 1.149 0 0 0-2.298 0v9.617h2.297z");
}

.nyu9ygbyh {
  stop-color: var(--svg-color--cdbfde, #CDBFDE);
}

.oo_u7tb1b {
  stop-color: var(--svg-color--e2daeb, #E2DAEB);
  stop-opacity: 0;
}

.oq3j5obbk {
  stop-color: var(--svg-color--4065b4, #4065B4);
}

.q1q7fsbcf {
  d: path("M13.937 12.681c.473.74.747 1.618.747 2.561v2.764l-.777.487a.22.22 0 0 1-.23 0L6.454 13.98a.41.41 0 0 1-.193-.35c0-.523.424-.948.948-.948z");
}

.q2664bbii {
  stop-color: var(--svg-color--8f616c, #8F616C);
}

.q53k2_j6z {
  d: path("M5.169 15.242a4.758 4.758 0 1 1 9.515 0v7.992a.25.25 0 0 1-.25.25H5.42a.25.25 0 0 1-.25-.25z");
}

.qleet2bok {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M5.49 24.555h9.198c.66 0 1.23-.458 1.23-1.063V14.69c0-2.82-2.49-5.273-5.826-5.275C6.94 9.25 4.259 11.38 4.259 14.69v8.802c0 .605.57 1.063 1.23 1.063Z");
}

.r_68sobta {
  stop-color: var(--svg-color--d0cbd7, #D0CBD7);
}

.r2t4_lbss {
  stop-color: var(--svg-color--632f53, #632F53);
  stop-opacity: 0;
}

.rbz9yubut {
  stop-color: var(--svg-color--cfcbd8, #CFCBD8);
}

.rznriwbau {
  d: path("M13.186 24.923h4.65v4.956h-4.65z");
}

.s2drkiaqw {
  stop-color: var(--svg-color--ff8e4e, #FF8E4E);
}

.s9x7vp8wh {
  stop-color: var(--svg-color--948aa4, #948AA4);
}

.sjagd30ip {
  fill: var(--svg-color--4473c1, #4473C1);
  d: path("M5.49 24.43h9.198c.61 0 1.105-.42 1.105-.938V14.69c0-2.743-2.428-5.15-5.704-5.15c-3.093-.163-5.705 1.92-5.705 5.15v8.802c0 .518.495.938 1.105.938");
}

.ubx36-iyc {
  d: path("M4.78 15.238a4.758 4.758 0 1 1 9.516 0v7.993a.25.25 0 0 1-.25.25H5.03a.25.25 0 0 1-.25-.25z");
}

.uk-817bee {
  width: 8.516px;
  height: 0.319px;
  x: 18.973px;
  y: 11.908px;
  fill: var(--svg-color--aea4bf, #AEA4BF);
  rx: 0.159px;
}

.usuc0321h {
  stop-color: var(--svg-color--636697, #636697);
}

.uuf7d16qw {
  stop-color: var(--svg-color--9571c7, #9571C7);
}

.uyqzj06di {
  stop-color: var(--svg-color--3255bf, #3255BF);
  stop-opacity: 0;
}

.v3rncsbye {
  stop-color: var(--svg-color--7d4261, #7D4261);
}

.w8uut-baw {
  stop-color: var(--svg-color--855a5d, #855A5D);
}

.wpldrkowr {
  stop-color: var(--svg-color--9f98a9, #9F98A9);
  stop-opacity: 0;
}

.wsxh4l0ai {
  stop-color: var(--svg-color--948da4, #948DA4);
  stop-opacity: 0;
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.wzxqf6jtq {
  stop-color: var(--svg-color--b6b6bd, #B6B6BD);
  stop-opacity: 0;
}

.xy9slpbvc {
  stop-color: var(--svg-color--e9e0f5, #E9E0F5);
}

.ycovydbur {
  stop-color: var(--svg-color--88858e, #88858E);
}

.yqciwabyz {
  stop-color: var(--svg-color--3255bf, #3255BF);
}

.zoc1v6h3d {
  stop-color: var(--svg-color--b0b0b7, #B0B0B7);
}

.zrqwy0bgb {
  stop-color: var(--svg-color--855a5d, #855A5D);
  stop-opacity: 0;
}

.zy76svb5r {
  stop-color: var(--svg-color--ccc4d7, #CCC4D7);
  stop-opacity: 0;
}

</style>
