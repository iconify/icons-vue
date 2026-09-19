<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iIvja2x)" class="vyipq1bmf"/><path fill="url(#iY1bCmb)" class="vyipq1bmf"/><path fill="url(#iy9Idzj)" class="vyipq1bmf"/><path fill="url(#iZOj3te)" class="vyipq1bmf"/><path fill="url(#isvsSPY)" class="vyipq1bmf"/><path fill="url(#iGGmCiD)" class="vyipq1bmf"/><path fill="url(#i7XhlJj)" class="vyipq1bmf"/><path fill="url(#igr29Cb)" class="vyipq1bmf"/><path fill="url(#ipFlr9b)" class="nd8w484vu"/><path fill="url(#i9fSUzb)" class="xxgphzb3p"/><path fill="url(#inC7Kzb)" class="w4t6comqh"/><path fill="url(#iV6gxVb)" class="w4t6comqh"/><path fill="url(#iWOgGmc)" class="im-_0-b2q"/><g filter="url(#iS5yx7c)"><path class="ges-v-gli"/></g><path fill="url(#iKgdIyb)" class="gsab22bej"/><path fill="url(#i41VgMt)" class="gsab22bej"/><path fill="url(#iqpsQ4i)" class="gsab22bej"/><path fill="url(#iMMZ9Kb)" class="gsab22bej"/><path fill="url(#ier7cLc)" class="tvcaag90c"/><path fill="url(#iY7ZCtd)" class="tvcaag90c"/><path fill="url(#iTpcGec)" class="tvcaag90c"/><path fill="url(#iwusWdc)" class="hw2g5z67e"/><path fill="url(#iYfDygb)" class="hw2g5z67e"/><path fill="url(#i06ROkd)" class="hw2g5z67e"/><path fill="url(#iged1Xt)" class="t39l27brc"/><path fill="url(#ixU0pii)" class="zarnxzuya"/><ellipse fill="url(#ixK4XSb)" class="oglvxgbpg"/><circle fill="url(#imgkU4c)" class="ur1s32_9s"/><circle fill="url(#iTzAH1b)" class="vh98c64ii"/><circle fill="url(#iNMeWSb)" class="huwykabmy"/><defs><radialGradient id="iY1bCmb" cx="0" cy="0" r="1" gradientTransform="matrix(-.3475 7.125 -5.8255 -.28412 16.035 27.875)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="b39m61b9a"/><stop offset=".898" class="l5oafwb0y"/></radialGradient><radialGradient id="iy9Idzj" cx="0" cy="0" r="1" gradientTransform="matrix(1.195 3.1875 -2.14612 .80458 10.93 29.438)" gradientUnits="userSpaceOnUse"><stop class="hn8u0vk9q"/><stop offset=".543" class="xqkt32x4y"/></radialGradient><radialGradient id="iZOj3te" cx="0" cy="0" r="1" gradientTransform="matrix(-.10875 1.40625 -.77103 -.05963 21.14 29.344)" gradientUnits="userSpaceOnUse"><stop class="ckouaxbqt"/><stop offset="1" class="xqkt32x4y"/></radialGradient><radialGradient id="isvsSPY" cx="0" cy="0" r="1" gradientTransform="matrix(.01562 .34375 -3.0275 .13761 19.063 29.125)" gradientUnits="userSpaceOnUse"><stop class="vuowtizzi"/><stop offset="1" class="ov_z5ubba"/></radialGradient><radialGradient id="iGGmCiD" cx="0" cy="0" r="1" gradientTransform="matrix(0 .25781 -2.531 0 13.219 29.688)" gradientUnits="userSpaceOnUse"><stop class="xn7uoevbp"/><stop offset="1" class="skhxmq8-h"/></radialGradient><radialGradient id="i7XhlJj" cx="0" cy="0" r="1" gradientTransform="matrix(0 .32812 -3.22127 0 13.14 28.93)" gradientUnits="userSpaceOnUse"><stop class="fqwu5wxww"/><stop offset="1" class="rehvr4b7b"/></radialGradient><radialGradient id="iV6gxVb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75002 3.31249 -2.51887 -1.33075 10.625 8.5)" gradientUnits="userSpaceOnUse"><stop class="d-rq2wb1b"/><stop offset="1" class="qtm9p2bwz"/></radialGradient><radialGradient id="i41VgMt" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 4.9375 -4.42282 .50387 19.563 10.938)" gradientUnits="userSpaceOnUse"><stop class="cjs0e2bpy"/><stop offset="1" class="zqbke8bkv"/></radialGradient><radialGradient id="iqpsQ4i" cx="0" cy="0" r="1" gradientTransform="rotate(108.939 .738 9.87)scale(6.73986 3.89166)" gradientUnits="userSpaceOnUse"><stop class="cjs0e2bpy"/><stop offset="1" class="zqbke8bkv"/></radialGradient><radialGradient id="iMMZ9Kb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.6875 -5.70968 0 20.125 14.5)" gradientUnits="userSpaceOnUse"><stop class="g7kyxec0w"/><stop offset="1" class="p5f43k3xg"/></radialGradient><radialGradient id="iY7ZCtd" cx="0" cy="0" r="1" gradientTransform="matrix(-.28125 1.78125 -1.55167 -.245 20.5 2.75)" gradientUnits="userSpaceOnUse"><stop offset=".631" class="tfm1g1blp"/><stop offset="1" class="te6x6tbzq"/></radialGradient><radialGradient id="iTpcGec" cx="0" cy="0" r="1" gradientTransform="rotate(96.654 8.38 10.988)scale(1.88772 .80902)" gradientUnits="userSpaceOnUse"><stop class="emhti9bee"/><stop offset="1" class="mh82o7als"/></radialGradient><radialGradient id="i06ROkd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .32532 -.79605 0 17.375 6.034)" gradientUnits="userSpaceOnUse"><stop class="z8ui3ebcd"/><stop offset="1" class="k9-g8lb7n"/></radialGradient><radialGradient id="ixK4XSb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.10937 -.66736 0 23.484 3.156)" gradientUnits="userSpaceOnUse"><stop offset=".169" class="yev9-nbwi"/><stop offset="1" class="d3kv23tmh"/></radialGradient><radialGradient id="imgkU4c" cx="0" cy="0" r="1" gradientTransform="rotate(123.101 4.322 10.265)scale(1.25887)" gradientUnits="userSpaceOnUse"><stop class="uev-v0jqi"/><stop offset="1" class="e1j0kxa8j"/></radialGradient><radialGradient id="iTzAH1b" cx="0" cy="0" r="1" gradientTransform="rotate(123.101 5.248 12.454)scale(1.25887)" gradientUnits="userSpaceOnUse"><stop class="xfqh38bid"/><stop offset=".799" class="rb_unpbgg"/></radialGradient><radialGradient id="iNMeWSb" cx="0" cy="0" r="1" gradientTransform="rotate(123.101 2.798 13.077)scale(1.25887)" gradientUnits="userSpaceOnUse"><stop class="ezo5teb1p"/><stop offset=".785" class="ntp0ec5qc"/></radialGradient><linearGradient id="iIvja2x" x1="16.035" x2="16.536" y1="28.688" y2="31.992" gradientUnits="userSpaceOnUse"><stop class="axp_mrbqm"/><stop offset=".481" class="gqk-igbou"/></linearGradient><linearGradient id="igr29Cb" x1="16.035" x2="16.035" y1="28.625" y2="28.844" gradientUnits="userSpaceOnUse"><stop class="iw__adckq"/><stop offset="1" class="c3eiz-bza"/></linearGradient><linearGradient id="ipFlr9b" x1="15.281" x2="16.813" y1="26.406" y2="26.406" gradientUnits="userSpaceOnUse"><stop class="ax4b4-bhn"/><stop offset=".1" class="oaewl7bec"/><stop offset=".34" class="tm5q9ibzx"/><stop offset=".605" class="zym42eb8b"/><stop offset=".863" class="o73r65bco"/><stop offset=".949" class="mbi4-_v6l"/></linearGradient><linearGradient id="i9fSUzb" x1="11.48" x2="11.48" y1="2" y2="10.96" gradientUnits="userSpaceOnUse"><stop offset=".565" class="s_h5g69kk"/><stop offset="1" class="k4avlmb8p"/></linearGradient><linearGradient id="inC7Kzb" x1="14.438" x2="8.16" y1="4.75" y2="7.938" gradientUnits="userSpaceOnUse"><stop class="mudbth5ig"/><stop offset=".502" class="t1d37odac"/><stop offset="1" class="u8spwucwd"/></linearGradient><linearGradient id="iWOgGmc" x1="16.025" x2="16.025" y1="6.02" y2="25.077" gradientUnits="userSpaceOnUse"><stop class="u7n4_kbom"/><stop offset=".147" class="m1cuxbp7h"/><stop offset=".681" class="z7s2nba5q"/><stop offset=".939" class="fz51wmb5d"/><stop offset="1" class="kpm-w-88c"/></linearGradient><linearGradient id="iKgdIyb" x1="16.029" x2="16.029" y1="23.83" y2="10.01" gradientUnits="userSpaceOnUse"><stop offset=".051" class="xsvvdu6rp"/><stop offset=".282" class="cq-mjff3f"/><stop offset=".521" class="z1cbw3b-d"/><stop offset=".969" class="qfzl5ccij"/><stop offset="1" class="i46bc3-mx"/></linearGradient><linearGradient id="ier7cLc" x1="17.797" x2="19.766" y1="5.281" y2="5.914" gradientUnits="userSpaceOnUse"><stop class="bnrrwvbjq"/><stop offset=".209" class="ijzn8pbjx"/><stop offset=".361" class="m4dxzccdb"/><stop offset=".788" class="i4uugxnhs"/><stop offset="1" class="mn9vxgbrj"/></linearGradient><linearGradient id="iwusWdc" x1="16.75" x2="18.75" y1="8.219" y2="8.719" gradientUnits="userSpaceOnUse"><stop class="kjjmdtb9q"/><stop offset=".237" class="gsprnw4gd"/><stop offset=".421" class="mczgnqb1a"/><stop offset=".675" class="dx3am_b5u"/><stop offset="1" class="n0g0obb5g"/></linearGradient><linearGradient id="iYfDygb" x1="17.918" x2="17.984" y1="6.034" y2="6.75" gradientUnits="userSpaceOnUse"><stop offset=".373" class="lnvmqcbun"/><stop offset=".788" class="b2qcq8xul"/></linearGradient><linearGradient id="iged1Xt" x1="21.11" x2="21.11" y1="1.992" y2="3.992" gradientUnits="userSpaceOnUse"><stop class="edfns081j"/><stop offset=".184" class="ek9uhlu2e"/><stop offset=".355" class="zoygsgbvz"/><stop offset=".84" class="kqxox0b2n"/><stop offset="1" class="j5gsn7pkp"/></linearGradient><linearGradient id="ixU0pii" x1="20.189" x2="22.784" y1="9.197" y2="18.278" gradientUnits="userSpaceOnUse"><stop offset=".344" class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><filter id="iS5yx7c" width="16.073" height="19.558" x="8.065" y="5.69" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_27486" stdDeviation=".28"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:tropical-drink" /></template>
<style>
.ax4b4-bhn {
  stop-color: var(--svg-color--a6c6e5, #A6C6E5);
}

.axp_mrbqm {
  stop-color: var(--svg-color--b2e5ff, #B2E5FF);
}

.b2qcq8xul {
  stop-color: var(--svg-color--f04c8c, #F04C8C);
  stop-opacity: 0;
}

.b39m61b9a {
  stop-color: var(--svg-color--bedbf3, #BEDBF3);
  stop-opacity: 0;
}

.bnrrwvbjq {
  stop-color: var(--svg-color--d95575, #D95575);
}

.c3eiz-bza {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
  stop-opacity: 0;
}

.cjs0e2bpy {
  stop-color: var(--svg-color--ffbc70, #FFBC70);
}

.ckouaxbqt {
  stop-color: var(--svg-color--afd8fa, #AFD8FA);
}

.cq-mjff3f {
  stop-color: var(--svg-color--f77b40, #F77B40);
}

.d-rq2wb1b {
  stop-color: var(--svg-color--4ca153, #4CA153);
}

.d3kv23tmh {
  stop-color: var(--svg-color--b90712, #B90712);
}

.dx3am_b5u {
  stop-color: var(--svg-color--ff74ac, #FF74AC);
}

.e1j0kxa8j {
  stop-color: var(--svg-color--efba40, #EFBA40);
}

.edfns081j {
  stop-color: var(--svg-color--e1515c, #E1515C);
}

.ek9uhlu2e {
  stop-color: var(--svg-color--df3a4d, #DF3A4D);
}

.emhti9bee {
  stop-color: var(--svg-color--c2395b, #C2395B);
}

.ezo5teb1p {
  stop-color: var(--svg-color--ffd059, #FFD059);
}

.fqwu5wxww {
  stop-color: var(--svg-color--b4e8ff, #B4E8FF);
}

.ft5dv1b6b {
  fill: none;
}

.fz51wmb5d {
  stop-color: var(--svg-color--b4e7fb, #B4E7FB);
}

.g7kyxec0w {
  stop-color: var(--svg-color--ffb370, #FFB370);
}

.ges-v-gli {
  fill: var(--svg-color--ade0ff, #ADE0FF);
  d: path("M22.824 13.506a21.3 21.3 0 0 1-1.91-6.608c-.047-.367-.336-.648-.7-.648h-8.217c-.363 0-.652.28-.699.658c-.251 2.264-.866 4.47-1.863 6.501a8.1 8.1 0 0 0-.67 5.041c.558 3.038 2.906 5.495 5.84 6.086c4.79.967 8.973-2.816 8.973-7.615c0-1.228-.27-2.39-.755-3.415");
}

.gqk-igbou {
  stop-color: var(--svg-color--b2f1ff, #B2F1FF);
}

.gsab22bej {
  d: path("M19.93 10.01h-7.78c-.38 0-.71.25-.82.62c-.35 1.16-.8 2.29-1.34 3.36c-.41.8-.65 1.66-.71 2.55c-.14 1.89.5 3.7 1.8 5.11a6.78 6.78 0 0 0 4.96 2.18c.13 0 .26 0 .39-.01a6.778 6.778 0 0 0 5.68-9.74a23 23 0 0 1-1.36-3.45a.855.855 0 0 0-.82-.62");
}

.gsprnw4gd {
  stop-color: var(--svg-color--ed78ad, #ED78AD);
}

.hn8u0vk9q {
  stop-color: var(--svg-color--a7c7e6, #A7C7E6);
}

.huwykabmy {
  cx: 14.996px;
  cy: 18.121px;
  r: 0.809px;
}

.hw2g5z67e {
  d: path("M17.517 6.034L16.14 10.01h2.187l1.368-3.976z");
}

.i46bc3-mx {
  stop-color: var(--svg-color--ff8c00, #FF8C00);
}

.i4uugxnhs {
  stop-color: var(--svg-color--f0427b, #F0427B);
}

.ijzn8pbjx {
  stop-color: var(--svg-color--e45580, #E45580);
}

.im-_0-b2q {
  d: path("M23.24 13.52a21.4 21.4 0 0 1-2.05-6.83a.757.757 0 0 0-.75-.67h-8.82c-.39 0-.7.29-.75.68c-.27 2.34-.93 4.62-2 6.72a8.1 8.1 0 0 0-.72 5.21c.6 3.14 3.12 5.68 6.27 6.29c5.14 1 9.63-2.91 9.63-7.87c0-1.27-.29-2.47-.81-3.53");
}

.iw__adckq {
  stop-color: var(--svg-color--b0dfff, #B0DFFF);
}

.j5gsn7pkp {
  stop-color: var(--svg-color--ce6b88, #CE6B88);
}

.k4avlmb8p {
  stop-color: var(--svg-color--1b8963, #1B8963);
}

.k9-g8lb7n {
  stop-color: var(--svg-color--e86c93, #E86C93);
  stop-opacity: 0;
}

.kjjmdtb9q {
  stop-color: var(--svg-color--dd82ab, #DD82AB);
}

.kpm-w-88c {
  stop-color: var(--svg-color--bbecfe, #BBECFE);
}

.kqxox0b2n {
  stop-color: var(--svg-color--d5374e, #D5374E);
}

.l5oafwb0y {
  stop-color: var(--svg-color--bbdaf5, #BBDAF5);
}

.lnvmqcbun {
  stop-color: var(--svg-color--ee4b8c, #EE4B8C);
}

.m1cuxbp7h {
  stop-color: var(--svg-color--a6c4df, #A6C4DF);
}

.m4dxzccdb {
  stop-color: var(--svg-color--e43a75, #E43A75);
}

.mbi4-_v6l {
  stop-color: var(--svg-color--b0d3f3, #B0D3F3);
}

.mczgnqb1a {
  stop-color: var(--svg-color--f76fac, #F76FAC);
}

.mh82o7als {
  stop-color: var(--svg-color--e33e67, #E33E67);
  stop-opacity: 0;
}

.mn9vxgbrj {
  stop-color: var(--svg-color--ed4178, #ED4178);
}

.mudbth5ig {
  stop-color: var(--svg-color--68c510, #68C510);
}

.n0g0obb5g {
  stop-color: var(--svg-color--ff7eb9, #FF7EB9);
}

.nd8w484vu {
  d: path("M16.78 28.61v-4.78h-1.5v4.78z");
}

.ntp0ec5qc {
  stop-color: var(--svg-color--f0bb49, #F0BB49);
}

.o73r65bco {
  stop-color: var(--svg-color--b5e8ff, #B5E8FF);
}

.oaewl7bec {
  stop-color: var(--svg-color--aedeff, #AEDEFF);
}

.oglvxgbpg {
  cx: 23.094px;
  cy: 2.992px;
  rx: 0.602px;
  ry: 1px;
}

.ov_z5ubba {
  stop-color: var(--svg-color--d4fcff, #D4FCFF);
  stop-opacity: 0;
}

.p5f43k3xg {
  stop-color: var(--svg-color--ffb370, #FFB370);
  stop-opacity: 0;
}

.qfzl5ccij {
  stop-color: var(--svg-color--ff9635, #FF9635);
}

.qtm9p2bwz {
  stop-color: var(--svg-color--419f4b, #419F4B);
  stop-opacity: 0;
}

.rb_unpbgg {
  stop-color: var(--svg-color--fac662, #FAC662);
}

.rehvr4b7b {
  stop-color: var(--svg-color--b5e9ff, #B5E9FF);
  stop-opacity: 0;
}

.s_h5g69kk {
  stop-color: var(--svg-color--25946a, #25946A);
}

.skhxmq8-h {
  stop-color: var(--svg-color--b9fffa, #B9FFFA);
  stop-opacity: 0;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t1d37odac {
  stop-color: var(--svg-color--65c213, #65C213);
}

.t39l27brc {
  d: path("M23.125 1.992h-2.8c-.734 0-.778.66-.778 1.008c0 .578.617.992.847.992h2.731z");
}

.te6x6tbzq {
  stop-color: var(--svg-color--dc3f50, #DC3F50);
  stop-opacity: 0;
}

.tfm1g1blp {
  stop-color: var(--svg-color--db3f50, #DB3F50);
}

.tm5q9ibzx {
  stop-color: var(--svg-color--b1e7ff, #B1E7FF);
}

.tvcaag90c {
  d: path("M23.125 2.002s-2.71-.01-3.297-.01c-.586 0-1.02.324-1.187.801s-2.5 7.217-2.5 7.217h2.187l2.07-6.018h2.727z");
}

.u7n4_kbom {
  stop-color: var(--svg-color--a4cfee, #A4CFEE);
}

.u8spwucwd {
  stop-color: var(--svg-color--60b43d, #60B43D);
}

.uev-v0jqi {
  stop-color: var(--svg-color--ffce51, #FFCE51);
}

.ur1s32_9s {
  cx: 14.996px;
  cy: 12.496px;
  r: 0.809px;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vh98c64ii {
  cx: 18.262px;
  cy: 15.105px;
  r: 0.809px;
}

.vuowtizzi {
  stop-color: var(--svg-color--c7fcff, #C7FCFF);
}

.vyipq1bmf {
  d: path("M20.38 28.61h-3.6v-8.73h-1.5v8.73h-3.6a.749.749 0 1 0 0 1.5h8.71a.749.749 0 1 0-.01-1.5");
}

.w4t6comqh {
  d: path("M11.48 9.8a3.32 3.32 0 1 0 0-6.64a3.32 3.32 0 0 0 0 6.64");
}

.xfqh38bid {
  stop-color: var(--svg-color--ffde76, #FFDE76);
}

.xn7uoevbp {
  stop-color: var(--svg-color--b9f0ff, #B9F0FF);
}

.xqkt32x4y {
  stop-color: var(--svg-color--badaf5, #BADAF5);
  stop-opacity: 0;
}

.xsvvdu6rp {
  stop-color: var(--svg-color--e57476, #E57476);
}

.xxgphzb3p {
  d: path("M11.48 10.96a4.48 4.48 0 1 0 0-8.96a4.48 4.48 0 0 0 0 8.96");
}

.yev9-nbwi {
  stop-color: var(--svg-color--d40f1c, #D40F1C);
}

.z1cbw3b-d {
  stop-color: var(--svg-color--fe8e34, #FE8E34);
}

.z7s2nba5q {
  stop-color: var(--svg-color--a9c4dc, #A9C4DC);
}

.z8ui3ebcd {
  stop-color: var(--svg-color--e76895, #E76895);
}

.zarnxzuya {
  d: path("M22.658 18.587c-.28 0-.5-.22-.5-.5c0-1.07-.24-2.09-.7-3.04a20.2 20.2 0 0 1-1.94-6.46a.51.51 0 0 1 .44-.56c.25-.04.52.16.56.44c.25 2.1.87 4.17 1.84 6.14c.53 1.09.8 2.26.8 3.48c0 .28-.22.5-.5.5");
}

.zoygsgbvz {
  stop-color: var(--svg-color--df4450, #DF4450);
}

.zqbke8bkv {
  stop-color: var(--svg-color--ffbc70, #FFBC70);
  stop-opacity: 0;
}

.zym42eb8b {
  stop-color: var(--svg-color--bcf1ff, #BCF1FF);
}

</style>
