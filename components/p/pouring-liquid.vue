<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iO9KYGg)" class="h8abcxbpx"/><path fill="url(#ijloWKb)" class="h8abcxbpx"/><path fill="url(#ifkhsec)" class="h8abcxbpx"/><path fill="url(#iSVS26u)" class="h8abcxbpx"/><path fill="url(#iQus7Ob)" class="h8abcxbpx"/><path fill="url(#iFQroQe)" class="h8abcxbpx"/><path fill="url(#irj9PNe)" class="h8abcxbpx"/><path fill="url(#iTOTbub)" class="mwk1i3x0v"/><path fill="url(#iJTA7Lc)" class="sv2o6czfa"/><path fill="url(#iJLtXgd)" class="sv2o6czfa"/><path fill="url(#iibuA3z)" class="sv2o6czfa"/><path class="ar8ci8bmf"/><path fill="url(#icBMO9d)" class="js4oht-3i"/><path fill="url(#i0Wci1c)" class="js4oht-3i"/><path fill="url(#iokpU2b)" class="eu91v1h9t"/><circle fill="url(#iRbFRdd)" class="nogm5acjr"/><circle fill="url(#ieYQVEb)" class="nogm5acjr"/><circle fill="url(#i9Voyib)" class="c83dwwypi"/><circle fill="url(#in0Sawc)" class="c83dwwypi"/><defs><radialGradient id="iFQroQe" cx="0" cy="0" r="1" gradientTransform="rotate(-163.302 11.039 3.722)scale(.65386 5.55786)" gradientUnits="userSpaceOnUse"><stop class="glxx0rhnw"/><stop offset="1" class="kh5ia6b9c"/></radialGradient><radialGradient id="irj9PNe" cx="0" cy="0" r="1" gradientTransform="rotate(17.101 -33.97 16.29)scale(.42592 2.69195)" gradientUnits="userSpaceOnUse"><stop class="glxx0rhnw"/><stop offset="1" class="kh5ia6b9c"/></radialGradient><radialGradient id="iJLtXgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .97075 -1.14063 0 28.873 28.058)" gradientUnits="userSpaceOnUse"><stop class="fi4qosbau"/><stop offset="1" class="ylbi4nbfw"/></radialGradient><radialGradient id="iibuA3z" cx="0" cy="0" r="1" gradientTransform="matrix(0 .67326 -.83035 0 23.753 26.68)" gradientUnits="userSpaceOnUse"><stop offset=".336" class="wo-bcebxb"/><stop offset="1" class="qapzy2flx"/></radialGradient><radialGradient id="icBMO9d" cx="0" cy="0" r="1" gradientTransform="matrix(2.06676 13.52783 -12.54247 1.91622 15.408 26.869)" gradientUnits="userSpaceOnUse"><stop offset=".597" class="szgx_gb1k"/><stop offset=".654" class="z2pkdp8lo"/><stop offset=".918" class="kwt2oi29d"/></radialGradient><radialGradient id="i0Wci1c" cx="0" cy="0" r="1" gradientTransform="rotate(-71.03 30.7 -1.999)scale(2.11923 3.08784)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="xglxe12_t"/><stop offset="1" class="cedy5rkmv"/></radialGradient><radialGradient id="iRbFRdd" cx="0" cy="0" r="1" gradientTransform="rotate(126.332 3.813 16.953)scale(2.43133)" gradientUnits="userSpaceOnUse"><stop class="n4a56oypz"/><stop offset=".572" class="b-l3csbyf"/><stop offset="1" class="dwsa4sb1k"/></radialGradient><radialGradient id="ieYQVEb" cx="0" cy="0" r="1" gradientTransform="rotate(92.603 -1.735 21.377)scale(.68963)" gradientUnits="userSpaceOnUse"><stop class="zgz7pccsd"/><stop offset="1" class="v3psdy_cu"/></radialGradient><radialGradient id="i9Voyib" cx="0" cy="0" r="1" gradientTransform="rotate(126.332 7.174 18.767)scale(1.8735)" gradientUnits="userSpaceOnUse"><stop class="n4a56oypz"/><stop offset=".572" class="b-l3csbyf"/><stop offset="1" class="dwsa4sb1k"/></radialGradient><radialGradient id="in0Sawc" cx="0" cy="0" r="1" gradientTransform="rotate(92.603 1.624 24.726)scale(.5314)" gradientUnits="userSpaceOnUse"><stop class="zgz7pccsd"/><stop offset="1" class="v3psdy_cu"/></radialGradient><linearGradient id="iO9KYGg" x1="12.652" x2="10.46" y1="5.199" y2="15.721" gradientUnits="userSpaceOnUse"><stop class="cf6m9zfff"/><stop offset=".111" class="q7m5mnbpu"/><stop offset="1" class="klg-94bnl"/></linearGradient><linearGradient id="ijloWKb" x1="12.652" x2="11.963" y1="4.51" y2="9.896" gradientUnits="userSpaceOnUse"><stop offset=".091" class="sogu6kb8i"/><stop offset=".218" class="ar9dcp5oc"/></linearGradient><linearGradient id="ifkhsec" x1="9.332" x2="11.62" y1="16.973" y2="11.458" gradientUnits="userSpaceOnUse"><stop offset=".052" class="l7ecy0bfn"/><stop offset=".351" class="pymxz1ref"/></linearGradient><linearGradient id="iSVS26u" x1="2.569" x2="11.62" y1="8.706" y2="11.458" gradientUnits="userSpaceOnUse"><stop offset=".052" class="l7ecy0bfn"/><stop offset=".145" class="pymxz1ref"/></linearGradient><linearGradient id="iQus7Ob" x1="20.731" x2="11.62" y1="13.529" y2="11.458" gradientUnits="userSpaceOnUse"><stop offset=".052" class="l7ecy0bfn"/><stop offset=".145" class="pymxz1ref"/></linearGradient><linearGradient id="iTOTbub" x1="20.328" x2="3.445" y1="8.393" y2="5.903" gradientUnits="userSpaceOnUse"><stop offset=".41" class="vc--wpv5i"/><stop offset=".852" class="stui2mbih"/></linearGradient><linearGradient id="iJTA7Lc" x1="21.992" x2="21.992" y1="26.994" y2="30" gradientUnits="userSpaceOnUse"><stop class="i9_ah4bkz"/><stop offset=".323" class="cf-45fbdh"/><stop offset=".604" class="jr7xnbmjs"/><stop offset="1" class="ei07jgbmp"/></linearGradient><linearGradient id="iokpU2b" x1="14.28" x2="13.588" y1="15.94" y2="17.599" gradientUnits="userSpaceOnUse"><stop class="a5qmadcwp"/><stop offset=".447" class="j_kgzi6tm"/><stop offset="1" class="ja9dv_e_x"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pouring-liquid" /></template>
<style>
.a5qmadcwp {
  stop-color: var(--svg-color--93d6ff, #93D6FF);
}

.ar8ci8bmf {
  fill: var(--svg-color--45baff, #45BAFF);
  d: path("M8.326 14.579a.75.75 0 0 1 .978-.414l7.737 3.216c4.886 2.147 6.397 5.288 6.936 9.142c.132.95-1.451 1.046-1.586.095c-.472-3.312-1.84-5.948-5.825-7.719l-7.829-3.335a.757.757 0 0 1-.411-.985");
}

.ar9dcp5oc {
  stop-color: var(--svg-color--b9d2fb, #B9D2FB);
  stop-opacity: 0;
}

.b-l3csbyf {
  stop-color: var(--svg-color--5abdff, #5ABDFF);
}

.c83dwwypi {
  cx: 26.044px;
  cy: 24.572px;
  r: 1.044px;
}

.cedy5rkmv {
  stop-color: var(--svg-color--44a2ea, #44A2EA);
  stop-opacity: 0;
}

.cf-45fbdh {
  stop-color: var(--svg-color--47a8f4, #47A8F4);
}

.cf6m9zfff {
  stop-color: var(--svg-color--bee4ff, #BEE4FF);
}

.dwsa4sb1k {
  stop-color: var(--svg-color--83c4ff, #83C4FF);
}

.ei07jgbmp {
  stop-color: var(--svg-color--5980f1, #5980F1);
}

.eu91v1h9t {
  d: path("M8.326 14.579a.75.75 0 0 1 .978-.414l7.737 3.216q1.027.452 1.866.962l-.478 1.566a12.7 12.7 0 0 0-1.863-1.01l-7.829-3.335a.757.757 0 0 1-.411-.985");
}

.fi4qosbau {
  stop-color: var(--svg-color--5eb5f9, #5EB5F9);
}

.ft5dv1b6b {
  fill: none;
}

.glxx0rhnw {
  stop-color: var(--svg-color--d5ffff, #D5FFFF);
}

.h8abcxbpx {
  d: path("M4.17 4.807c.141-.53.65-.873 1.194-.806L21.25 5.966a.783.783 0 0 1 .66.977L18.537 19.65a.94.94 0 0 1-1.278.622l-14.67-6.286a.97.97 0 0 1-.555-1.142z");
}

.i9_ah4bkz {
  stop-color: var(--svg-color--48a3df, #48A3DF);
}

.j_kgzi6tm {
  stop-color: var(--svg-color--9adfff, #9ADFFF);
}

.ja9dv_e_x {
  stop-color: var(--svg-color--99c9ff, #99C9FF);
}

.jr7xnbmjs {
  stop-color: var(--svg-color--3e97f3, #3E97F3);
}

.js4oht-3i {
  d: path("M8.326 14.579a.75.75 0 0 1 .978-.414l7.737 3.216c4.886 2.147 6.397 5.288 6.936 9.142c.132.95-1.451 1.046-1.586.095c-.472-3.312-1.84-5.948-5.825-7.719l-7.829-3.335a.757.757 0 0 1-.411-.985");
}

.kh5ia6b9c {
  stop-color: var(--svg-color--d5ffff, #D5FFFF);
  stop-opacity: 0;
}

.klg-94bnl {
  stop-color: var(--svg-color--c8f2ff, #C8F2FF);
}

.kwt2oi29d {
  stop-color: var(--svg-color--66cbff, #66CBFF);
}

.l7ecy0bfn {
  stop-color: var(--svg-color--c3d5fa, #C3D5FA);
}

.mwk1i3x0v {
  d: path("M19.775 7.602c.344.043.59.366.549.721a.633.633 0 0 1-.7.566L5.712 7.168l.33-1.265z");
}

.n4a56oypz {
  stop-color: var(--svg-color--76d5ff, #76D5FF);
}

.nogm5acjr {
  cx: 19.08px;
  cy: 24.529px;
  r: 1.355px;
}

.pymxz1ref {
  stop-color: var(--svg-color--c1e9ff, #C1E9FF);
  stop-opacity: 0;
}

.q7m5mnbpu {
  stop-color: var(--svg-color--c0ebff, #C0EBFF);
}

.qapzy2flx {
  stop-color: var(--svg-color--56c3f7, #56C3F7);
  stop-opacity: 0;
}

.sogu6kb8i {
  stop-color: var(--svg-color--b9cef1, #B9CEF1);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.sv2o6czfa {
  d: path("M23.977 26.523a.67.67 0 0 0 .66.583H28.5c.829 0 1.5.676 1.5 1.51c0 .833-.671 1.384-1.5 1.384H15.483c-.828 0-1.5-.551-1.5-1.385c0-.833.672-1.51 1.5-1.51h6.479a.43.43 0 0 0 .429-.487c-.266-1.868 1.274-2.325 1.586-.095");
}

.szgx_gb1k {
  stop-color: var(--svg-color--4ebaff, #4EBAFF);
}

.v3psdy_cu {
  stop-color: var(--svg-color--73d4ff, #73D4FF);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.wo-bcebxb {
  stop-color: var(--svg-color--4fb8f3, #4FB8F3);
}

.xglxe12_t {
  stop-color: var(--svg-color--41a3ec, #41A3EC);
}

.ylbi4nbfw {
  stop-color: var(--svg-color--54b2f6, #54B2F6);
  stop-opacity: 0;
}

.z2pkdp8lo {
  stop-color: var(--svg-color--60d7ff, #60D7FF);
}

.zgz7pccsd {
  stop-color: var(--svg-color--73d3ff, #73D3FF);
}

</style>
