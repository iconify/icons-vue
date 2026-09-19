<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iqC3Jsb)"><path fill="url(#iO16b5f)" class="jif-6mbgi"/></g><g filter="url(#issEKhe)"><path class="gmx0zpb5q"/></g><g filter="url(#ilnSMje)"><path fill="url(#it2Vjve)" class="cmxb_vbgd"/></g><path fill="url(#in1YA6c)" class="cmxb_vbgd"/><rect fill="url(#itTqd9c)" class="tk8f-526c"/><rect fill="url(#i251fjd)" class="ly5q6gs_z"/><rect fill="url(#i1tCdsc)" class="p89iw-vpm"/><rect fill="url(#i9YLU3b)" class="jc9gxmfsj"/><path fill="url(#i7HEiBc)" class="zr-ojxblc"/><path fill="url(#iJJ6NNb)" class="zr-ojxblc"/><path fill="url(#i1uUFda)" class="zr-ojxblc"/><path fill="url(#i8389cd)" class="zr-ojxblc"/><path fill="url(#izkNU7d)" class="p1t_l5hgs"/><path fill="url(#iRyBbLe)" class="p1t_l5hgs"/><path fill="url(#iQoPbdd)" class="p1t_l5hgs"/><path fill="url(#i7IAuuc)" class="ocvmqccgu"/><path fill="url(#i7mzdNb)" class="ocvmqccgu"/><path fill="url(#iodKx5c)" class="ocvmqccgu"/><path fill="url(#iVLdnHC)" class="mtztoybmy"/><path fill="url(#ioIdqBc)" class="mtztoybmy"/><path fill="url(#iYaTETj)" class="rbqahqbti"/><defs><linearGradient id="iO16b5f" x1="16" x2="16" y1="2.043" y2="30.883" gradientUnits="userSpaceOnUse"><stop class="t5q2wtbwt"/><stop offset="1" class="iwajz3bda"/></linearGradient><linearGradient id="it2Vjve" x1="20.539" x2="23.18" y1="8.707" y2="6.066" gradientUnits="userSpaceOnUse"><stop class="zlu_x2p9s"/><stop offset="1" class="tgc6tswtj"/></linearGradient><linearGradient id="in1YA6c" x1="23.773" x2="22.516" y1="5.551" y2="6.82" gradientUnits="userSpaceOnUse"><stop offset=".119" class="xsa_hacwb"/><stop offset=".577" class="vo7sejkzk"/></linearGradient><linearGradient id="itTqd9c" x1="9.039" x2="22.953" y1="12.492" y2="12.492" gradientUnits="userSpaceOnUse"><stop class="hnx2_xbhl"/><stop offset="1" class="tg8tcbcty"/></linearGradient><linearGradient id="i251fjd" x1="9.039" x2="22.953" y1="15.492" y2="15.492" gradientUnits="userSpaceOnUse"><stop class="hnx2_xbhl"/><stop offset="1" class="tg8tcbcty"/></linearGradient><linearGradient id="i1tCdsc" x1="9.039" x2="22.953" y1="18.492" y2="18.492" gradientUnits="userSpaceOnUse"><stop class="hnx2_xbhl"/><stop offset="1" class="tg8tcbcty"/></linearGradient><linearGradient id="i9YLU3b" x1="9.039" x2="18.023" y1="21.492" y2="21.492" gradientUnits="userSpaceOnUse"><stop class="hnx2_xbhl"/><stop offset="1" class="tg8tcbcty"/></linearGradient><linearGradient id="iJJ6NNb" x1="16.154" x2="17.087" y1="20.493" y2="21.584" gradientUnits="userSpaceOnUse"><stop class="aenoi9yww"/><stop offset="1" class="a0kkuey7x"/></linearGradient><linearGradient id="i1uUFda" x1="22.841" x2="21.707" y1="23.566" y2="22.414" gradientUnits="userSpaceOnUse"><stop class="h0rwudxnf"/><stop offset="1" class="ai9dhbb0o"/></linearGradient><linearGradient id="izkNU7d" x1="11.304" x2="12.766" y1="27.483" y2="30.373" gradientUnits="userSpaceOnUse"><stop class="tid-kzbsk"/><stop offset="1" class="sx-7ahj_y"/></linearGradient><linearGradient id="iRyBbLe" x1="13.331" x2="12.952" y1="27.809" y2="28.124" gradientUnits="userSpaceOnUse"><stop offset=".207" class="yup415fjt"/><stop offset="1" class="crmnj0t8r"/></linearGradient><linearGradient id="iQoPbdd" x1="9.748" x2="11.137" y1="27.226" y2="27.487" gradientUnits="userSpaceOnUse"><stop class="lizd6-glu"/><stop offset="1" class="husszjb7z"/></linearGradient><linearGradient id="i7IAuuc" x1="28.628" x2="25.643" y1="15.108" y2="17.518" gradientUnits="userSpaceOnUse"><stop class="r_asvnbec"/><stop offset="1" class="yeknt5b_t"/></linearGradient><linearGradient id="i7mzdNb" x1="23.831" x2="25.778" y1="14.385" y2="16.575" gradientUnits="userSpaceOnUse"><stop class="rwcthpbkj"/><stop offset="1" class="pbxtx1bcn"/></linearGradient><linearGradient id="iVLdnHC" x1="22.041" x2="24.516" y1="16.081" y2="18.822" gradientUnits="userSpaceOnUse"><stop class="puojsyb6r"/><stop offset="1" class="j255snbex"/></linearGradient><linearGradient id="ioIdqBc" x1="25.871" x2="24.492" y1="21.119" y2="19.485" gradientUnits="userSpaceOnUse"><stop class="nwbvzjbuh"/><stop offset="1" class="jpy47xbyl"/></linearGradient><linearGradient id="iYaTETj" x1="10.053" x2="10.657" y1="28.982" y2="30.021" gradientUnits="userSpaceOnUse"><stop class="t_fd-nb-a"/><stop offset="1" class="gpqvdnbxd"/></linearGradient><radialGradient id="i7HEiBc" cx="0" cy="0" r="1" gradientTransform="matrix(9.98063 -8.37694 5.1962 6.19096 12.835 27.572)" gradientUnits="userSpaceOnUse"><stop class="z059-eb0z"/><stop offset="1" class="yqap_vurx"/></radialGradient><radialGradient id="i8389cd" cx="0" cy="0" r="1" gradientTransform="matrix(9.3224 -7.60972 1.70167 2.08466 12.682 27.432)" gradientUnits="userSpaceOnUse"><stop class="yjtw_3cqd"/><stop offset="1" class="ddi0xzb7k"/></radialGradient><radialGradient id="iodKx5c" cx="0" cy="0" r="1" gradientTransform="matrix(-.70174 .57568 -1.30777 -1.59415 28.01 15.671)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="s1ej_tb8x"/><stop offset="1" class="dhp8okbbn"/></radialGradient><filter id="iqC3Jsb" width="22.322" height="28.314" x="4.939" y="1.743" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.768627 0 0 0 0 0.85098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22438"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.690196 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_22438" result="effect2_innerShadow_18_22438"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.65098 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_22438" result="effect3_innerShadow_18_22438"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.952941 0 0 0 0 0.941176 0 0 0 0 0.964706 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_18_22438" result="effect4_innerShadow_18_22438"/></filter><filter id="issEKhe" width="7.974" height="8.363" x="19.199" y="1.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_22438" stdDeviation=".25"/></filter><filter id="ilnSMje" width="7.29" height="7.414" x="19.771" y="1.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.611765 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22438"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.67451 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_22438" result="effect2_innerShadow_18_22438"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:memo" /></template>
<style>
.a0kkuey7x {
  stop-color: var(--svg-color--ee9b6a, #EE9B6A);
  stop-opacity: 0;
}

.aenoi9yww {
  stop-color: var(--svg-color--ee9b6a, #EE9B6A);
}

.ai9dhbb0o {
  stop-color: var(--svg-color--e66a62, #E66A62);
  stop-opacity: 0;
}

.cmxb_vbgd {
  d: path("M20.04 2.348c0-.202-.159-.282-.269-.303a1 1 0 0 1 .644.29l6.253 6.254a1 1 0 0 1 .244.4a1 1 0 0 1 .049.307v.063c0-.232-.168-.37-.293-.37h-5.429a1.2 1.2 0 0 1-1.2-1.2z");
}

.crmnj0t8r {
  stop-color: var(--svg-color--fcb196, #FCB196);
  stop-opacity: 0;
}

.ddi0xzb7k {
  stop-color: var(--svg-color--ff994d, #FF994D);
  stop-opacity: 0;
}

.dhp8okbbn {
  stop-color: var(--svg-color--ff786d, #FF786D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gmx0zpb5q {
  fill: var(--svg-color--d2c5df, #D2C5DF);
  d: path("M19.751 2.457c0-.201.058-.33-.052-.352c.104.007.256.045.352.083c.123.048-.03.155.067.249l.009.008l6.253 6.253a1 1 0 0 1 .293.708v.063c0-.232-.168-.371-.293-.371h-5.429a1.2 1.2 0 0 1-1.2-1.2z");
}

.gpqvdnbxd {
  stop-color: var(--svg-color--450f51, #450F51);
}

.h0rwudxnf {
  stop-color: var(--svg-color--e66a62, #E66A62);
}

.hnx2_xbhl {
  stop-color: var(--svg-color--9c96a2, #9C96A2);
}

.husszjb7z {
  stop-color: var(--svg-color--debca3, #DEBCA3);
  stop-opacity: 0;
}

.iwajz3bda {
  stop-color: var(--svg-color--cec1d5, #CEC1D5);
}

.j255snbex {
  stop-color: var(--svg-color--e8defa, #E8DEFA);
}

.jc9gxmfsj {
  width: 8.984px;
  height: 0.992px;
  x: 9.039px;
  y: 20.996px;
  rx: 0.496px;
}

.jif-6mbgi {
  d: path("M20.415 2.336a1 1 0 0 0-.707-.293H6.439a1.4 1.4 0 0 0-1.4 1.4v25.114a1.4 1.4 0 0 0 1.4 1.4h19.122a1.4 1.4 0 0 0 1.4-1.4V9.297a1 1 0 0 0-.293-.708z");
}

.jpy47xbyl {
  stop-color: var(--svg-color--c9b9e0, #C9B9E0);
  stop-opacity: 0;
}

.lizd6-glu {
  stop-color: var(--svg-color--debca3, #DEBCA3);
}

.ly5q6gs_z {
  width: 13.914px;
  height: 0.992px;
  x: 9.039px;
  y: 14.996px;
  rx: 0.496px;
}

.mtztoybmy {
  d: path("m20.85 16.963l2.31-1.895l3.853 4.697l-2.31 1.895z");
}

.nwbvzjbuh {
  stop-color: var(--svg-color--c9b9e0, #C9B9E0);
}

.ocvmqccgu {
  d: path("m27.013 19.765l2.305-1.89a.994.994 0 0 0 .138-1.4l-2.593-3.16a.994.994 0 0 0-1.398-.138l-2.305 1.891z");
}

.p1t_l5hgs {
  d: path("M9.843 29.795a.133.133 0 0 0 .13.157l4.353.011a.66.66 0 0 0 .354-.101l.109-.068l-3.854-4.698l-.074.074a.66.66 0 0 0-.183.343z");
}

.p89iw-vpm {
  width: 13.914px;
  height: 0.992px;
  x: 9.039px;
  y: 17.996px;
  rx: 0.496px;
}

.pbxtx1bcn {
  stop-color: var(--svg-color--f1553e, #F1553E);
  stop-opacity: 0;
}

.puojsyb6r {
  stop-color: var(--svg-color--c5c4cb, #C5C4CB);
}

.r_asvnbec {
  stop-color: var(--svg-color--ff6153, #FF6153);
}

.rbqahqbti {
  d: path("M9.972 29.952a.133.133 0 0 1-.13-.158l.294-1.501l1.364 1.663z");
}

.rwcthpbkj {
  stop-color: var(--svg-color--f1553e, #F1553E);
}

.s1ej_tb8x {
  stop-color: var(--svg-color--ff786d, #FF786D);
}

.sx-7ahj_y {
  stop-color: var(--svg-color--ce7a98, #CE7A98);
}

.t_fd-nb-a {
  stop-color: var(--svg-color--461e49, #461E49);
}

.t5q2wtbwt {
  stop-color: var(--svg-color--e4dcea, #E4DCEA);
}

.tg8tcbcty {
  stop-color: var(--svg-color--9a95a1, #9A95A1);
}

.tgc6tswtj {
  stop-color: var(--svg-color--bdb4c1, #BDB4C1);
}

.tid-kzbsk {
  stop-color: var(--svg-color--d8a587, #D8A587);
}

.tk8f-526c {
  width: 13.914px;
  height: 0.992px;
  x: 9.039px;
  y: 11.996px;
  rx: 0.496px;
}

.vo7sejkzk {
  stop-color: var(--svg-color--cbc7d0, #CBC7D0);
  stop-opacity: 0;
}

.xsa_hacwb {
  stop-color: var(--svg-color--dbdadc, #DBDADC);
}

.yeknt5b_t {
  stop-color: var(--svg-color--ff6154, #FF6154);
}

.yjtw_3cqd {
  stop-color: var(--svg-color--ff994d, #FF994D);
}

.yqap_vurx {
  stop-color: var(--svg-color--f3633d, #F3633D);
}

.yup415fjt {
  stop-color: var(--svg-color--ffc09f, #FFC09F);
}

.z059-eb0z {
  stop-color: var(--svg-color--ff9130, #FF9130);
}

.zlu_x2p9s {
  stop-color: var(--svg-color--cac2ce, #CAC2CE);
}

.zr-ojxblc {
  d: path("M25.073 13.499a1.5 1.5 0 0 1 2.111.208l1.95 2.378a1.5 1.5 0 0 1-.207 2.11l-14.138 11.6l-3.854-4.698z");
}

</style>
