<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iwRtCEd)" class="y3pofu6wv"/><path fill="url(#imDx4xb)" class="y3pofu6wv"/><path fill="url(#iPVVD6Q)" class="y3pofu6wv"/><path fill="url(#iuniN4b)" class="s4owmcb4u"/><path fill="url(#iPVVD6Q)" class="s4owmcb4u"/><path fill="url(#iYvaPmc)" class="s4owmcb4u"/><path fill="url(#iWxlfUd)" class="s4owmcb4u"/><path fill="url(#iccqZ9d)" class="s4owmcb4u"/><path fill="url(#iFqI6Kb)" class="de0jzeb8a"/><path fill="url(#ik8JeFe)" class="de0jzeb8a"/><path fill="url(#iDgcAEX)" class="de0jzeb8a"/><g filter="url(#ibXNhec)"><path fill="url(#i2NuLQP)" class="scplo0a-u"/></g><path fill="url(#iTdJwwd)" class="c86sfqbyn"/><path fill="url(#itU8Ptc)" class="ddqse6bwo"/><path fill="url(#iG1cVLb)" class="ddqse6bwo"/><path fill="url(#iSFQTNe)" class="ddqse6bwo"/><path fill="url(#ia0NguY)" class="ddqse6bwo"/><path fill="url(#iQ3KhdU)" class="vxz37_bmw"/><g filter="url(#itW1zJd)"><path fill="url(#iP50mdT)" class="tqe2hx37i"/></g><defs><linearGradient id="iwRtCEd" x1="21.997" x2="21.997" y1="2" y2="30" gradientUnits="userSpaceOnUse"><stop class="h_j9u0wvt"/><stop offset=".994" class="kt__1405u"/></linearGradient><linearGradient id="imDx4xb" x1="34.188" x2="13.987" y1="25.5" y2="25.5" gradientUnits="userSpaceOnUse"><stop class="vtqm2fkem"/><stop offset=".285" class="zmi-w8b8u"/><stop offset=".442" class="q3aihcb-p"/><stop offset=".517" class="te_zdzlam"/><stop offset=".625" class="j031c9vcv"/><stop offset="1" class="soznorbgb"/></linearGradient><linearGradient id="iPVVD6Q" x1="21.992" x2="21.992" y1="13.375" y2="30" gradientUnits="userSpaceOnUse"><stop offset=".932" class="qhjl5jbyk"/><stop offset="1" class="d58m67bek"/></linearGradient><linearGradient id="iuniN4b" x1="34.188" x2="13.987" y1="25.5" y2="25.5" gradientUnits="userSpaceOnUse"><stop class="vtqm2fkem"/><stop offset=".362" class="zmi-w8b8u"/><stop offset=".446" class="q3aihcb-p"/><stop offset=".563" class="te_zdzlam"/><stop offset=".727" class="j031c9vcv"/><stop offset="1" class="soznorbgb"/></linearGradient><linearGradient id="iFqI6Kb" x1="28.892" x2="15.563" y1="3.75" y2="3.75" gradientUnits="userSpaceOnUse"><stop class="s4hzjir3e"/><stop offset=".283" class="xbvfcib7n"/><stop offset=".727" class="xejl3krva"/><stop offset="1" class="soznorbgb"/></linearGradient><linearGradient id="i2NuLQP" x1="32.901" x2="15" y1="24.629" y2="24.629" gradientUnits="userSpaceOnUse"><stop class="vtqm2fkem"/><stop offset=".285" class="zmi-w8b8u"/><stop offset=".442" class="q3aihcb-p"/><stop offset=".517" class="te_zdzlam"/><stop offset=".625" class="j031c9vcv"/><stop offset="1" class="soznorbgb"/></linearGradient><linearGradient id="iTdJwwd" x1="15.938" x2="27.375" y1="6" y2="6" gradientUnits="userSpaceOnUse"><stop class="pc49xt7yg"/><stop offset=".552" class="xe2fywbpc"/><stop offset="1" class="h-ffyib-o"/></linearGradient><linearGradient id="itU8Ptc" x1="2.008" x2="17.75" y1="26.25" y2="26.25" gradientUnits="userSpaceOnUse"><stop class="e-sb713ev"/><stop offset=".401" class="o5dtk6b5q"/><stop offset=".663" class="zt2lgydao"/><stop offset=".917" class="h0sxz2rkn"/></linearGradient><linearGradient id="iG1cVLb" x1="9.512" x2="9.512" y1="20.469" y2="30" gradientUnits="userSpaceOnUse"><stop offset=".895" class="qhjl5jbyk"/><stop offset="1" class="d58m67bek"/></linearGradient><linearGradient id="iSFQTNe" x1="9.512" x2="9.512" y1="20.469" y2="21.156" gradientUnits="userSpaceOnUse"><stop class="e_5hjqbcc"/><stop offset=".227" class="j_vpbaccj"/></linearGradient><linearGradient id="iQ3KhdU" x1="2.008" x2="17.016" y1="24.367" y2="24.367" gradientUnits="userSpaceOnUse"><stop class="nivf3518y"/><stop offset=".466" class="x4q9_8bdq"/><stop offset="1" class="xbw6tsabn"/></linearGradient><linearGradient id="iP50mdT" x1="22.117" x2="18.993" y1="7.401" y2="7.401" gradientUnits="userSpaceOnUse"><stop class="bl9os8tuk"/><stop offset="1" class="ke1l66b0w"/></linearGradient><radialGradient id="iYvaPmc" cx="0" cy="0" r="1" gradientTransform="rotate(131.096 10.246 13.71)scale(14.9281 12.3347)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="vc--wpv5i"/><stop offset=".442" class="f-mngrbdc"/><stop offset=".778" class="mdt4h0bif"/><stop offset=".918" class="j0738bbae"/></radialGradient><radialGradient id="iWxlfUd" cx="0" cy="0" r="1" gradientTransform="matrix(-.01564 1.67188 -5.12643 -.04796 26.563 7.937)" gradientUnits="userSpaceOnUse"><stop offset=".25" class="vc--wpv5i"/><stop offset=".82" class="stui2mbih"/></radialGradient><radialGradient id="iccqZ9d" cx="0" cy="0" r="1" gradientTransform="matrix(-8.94579 6.9626 -11.57538 -14.87245 30.938 9.188)" gradientUnits="userSpaceOnUse"><stop class="j_l_86bdp"/><stop offset="1" class="sjfd5obmd"/></radialGradient><radialGradient id="ik8JeFe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.21875 -4.82986 0 26.36 7.688)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="qi6wetglj"/><stop offset="1" class="jn6jhl4cy"/></radialGradient><radialGradient id="iDgcAEX" cx="0" cy="0" r="1" gradientTransform="matrix(0 .625 -8.1875 0 26.75 2.5)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="ia0NguY" cx="0" cy="0" r="1" gradientTransform="matrix(0 .57813 -6.07031 0 14.625 21.219)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></radialGradient><filter id="ibXNhec" width="17.188" height="16.125" x="13.5" y="13.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28772" stdDeviation=".75"/></filter><filter id="itW1zJd" width="5.547" height="2.875" x="17.375" y="6.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28772" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:sake" /></template>
<style>
.bl9os8tuk {
  stop-color: var(--svg-color--cfc8dd, #CFC8DD);
}

.c86sfqbyn {
  d: path("M28.397 4h-12.8c.35.75.83 1.42 1.41 2h9.98c.58-.58 1.06-1.25 1.41-2");
}

.d58m67bek {
  stop-color: var(--svg-color--cca5f3, #CCA5F3);
}

.ddqse6bwo {
  d: path("M2.008 21.358v7.36c0 .845.18 1.282.883 1.282h13.187c.547 0 .938-.375.938-1.281v-7.36c0-.422-.25-.89-.907-.89H2.84c-.506 0-.831.36-.831.89");
}

.de0jzeb8a {
  d: path("M25.856 7.562a1.48 1.48 0 0 1 .54-1.042a7.07 7.07 0 0 0 2.48-3.91a.492.492 0 0 0-.48-.61h-12.8c-.32 0-.56.3-.49.61a7.07 7.07 0 0 0 2.48 3.91c.337.265.52.647.546 1.042z");
}

.e_5hjqbcc {
  stop-color: var(--svg-color--bebebf, #BEBEBF);
}

.e-sb713ev {
  stop-color: var(--svg-color--a7a1b2, #A7A1B2);
}

.f-mngrbdc {
  stop-color: var(--svg-color--d9d6e3, #D9D6E3);
}

.ft5dv1b6b {
  fill: none;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h-ffyib-o {
  stop-color: var(--svg-color--3994f2, #3994F2);
}

.h0sxz2rkn {
  stop-color: var(--svg-color--f0ebfd, #F0EBFD);
}

.j_l_86bdp {
  stop-color: var(--svg-color--f6f8ff, #F6F8FF);
}

.j_vpbaccj {
  stop-color: var(--svg-color--bebebf, #BEBEBF);
  stop-opacity: 0;
}

.j031c9vcv {
  stop-color: var(--svg-color--d6c8ee, #D6C8EE);
}

.j0738bbae {
  stop-color: var(--svg-color--a5a4aa, #A5A4AA);
}

.jn6jhl4cy {
  stop-color: var(--svg-color--dfdaee, #DFDAEE);
  stop-opacity: 0;
}

.ke1l66b0w {
  stop-color: var(--svg-color--a9a4b5, #A9A4B5);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.mdt4h0bif {
  stop-color: var(--svg-color--b0adba, #B0ADBA);
}

.nivf3518y {
  stop-color: var(--svg-color--477cbc, #477CBC);
}

.o5dtk6b5q {
  stop-color: var(--svg-color--dfd1f5, #DFD1F5);
}

.pc49xt7yg {
  stop-color: var(--svg-color--3974c5, #3974C5);
}

.q3aihcb-p {
  stop-color: var(--svg-color--f7f0ff, #F7F0FF);
}

.qhjl5jbyk {
  stop-color: var(--svg-color--d5b4fb, #D5B4FB);
  stop-opacity: 0;
}

.qi6wetglj {
  stop-color: var(--svg-color--f7f6ff, #F7F6FF);
}

.s4hzjir3e {
  stop-color: var(--svg-color--dad7e4, #DAD7E4);
}

.s4owmcb4u {
  d: path("m27.927 10.62l-1.71-1.97a1.48 1.48 0 0 1-.361-1.088a1.48 1.48 0 0 1 .54-1.042h-8.81c.337.265.52.647.546 1.042a1.52 1.52 0 0 1-.365 1.088l-1.71 1.97a8.45 8.45 0 0 0-2.07 5.53h16.01c0-2.03-.73-4-2.07-5.53");
}

.scplo0a-u {
  d: path("M15.072 15.438a7 7 0 0 0-.072 1.02V27.74c0 .454.372.822.833.822h12.522c.46 0 .832-.368.832-.822V16.457q0-.514-.071-1.02z");
}

.sjfd5obmd {
  stop-color: var(--svg-color--ebecf7, #EBECF7);
  stop-opacity: 0;
}

.soznorbgb {
  stop-color: var(--svg-color--a6a1b0, #A6A1B0);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.te_zdzlam {
  stop-color: var(--svg-color--e8dcfd, #E8DCFD);
}

.tqe2hx37i {
  d: path("M18.814 7.219h3.108v.875h-3.108l-.439-.438z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vtqm2fkem {
  stop-color: var(--svg-color--ebe9f4, #EBE9F4);
}

.vxz37_bmw {
  d: path("M2.008 22.383h15.008v1.984H2.008z");
}

.x4q9_8bdq {
  stop-color: var(--svg-color--3588f6, #3588F6);
}

.xbvfcib7n {
  stop-color: var(--svg-color--dad1eb, #DAD1EB);
}

.xbw6tsabn {
  stop-color: var(--svg-color--48adff, #48ADFF);
}

.xe2fywbpc {
  stop-color: var(--svg-color--3079e1, #3079E1);
}

.xejl3krva {
  stop-color: var(--svg-color--b7abcb, #B7ABCB);
}

.y3pofu6wv {
  d: path("m27.927 10.62l-1.71-1.97c-.55-.63-.47-1.6.18-2.13a7.07 7.07 0 0 0 2.48-3.91a.492.492 0 0 0-.48-.61h-12.8c-.32 0-.56.3-.49.61a7.07 7.07 0 0 0 2.48 3.91c.66.52.73 1.49.18 2.13l-1.71 1.97a8.45 8.45 0 0 0-2.07 5.53v12.91c0 .52.42.94.94.94h14.13c.52 0 .94-.42.94-.94V16.15c0-2.03-.73-4-2.07-5.53");
}

.zmi-w8b8u {
  stop-color: var(--svg-color--fbf6ff, #FBF6FF);
}

.zt2lgydao {
  stop-color: var(--svg-color--fcf2ff, #FCF2FF);
}

</style>
