<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iYfu29b)" class="z6co97pbh"/><path fill="url(#iBKD34c)" class="z6co97pbh"/><path fill="url(#iYQ9QZs)" class="z6co97pbh"/><path class="wcsuz9b-d"/><path fill="url(#it7jZMc)" class="g_zp97ben"/><path fill="url(#i5nVH7b)" class="g_zp97ben"/><path fill="url(#iZQ1f2c)" class="g_zp97ben"/><path fill="url(#ildjWtd)" class="g_zp97ben"/><path fill="url(#iTt1EYc)" class="g_zp97ben"/><path fill="url(#iSKnkLb)" class="g_zp97ben"/><path fill="url(#iySEB3i)" class="g_zp97ben"/><path fill="url(#i9deNiH)" class="g_zp97ben"/><path fill="url(#iIZvByc)" class="g_zp97ben"/><path fill="url(#iEiZiwc)" class="g_zp97ben"/><path fill="url(#iphpjhT)" class="g_zp97ben"/><path fill="url(#i7NnORc)" class="g_zp97ben"/><path fill="url(#ijDpHwb)" class="g_zp97ben"/><path fill="url(#i4kpRqe)" class="g_zp97ben"/><g filter="url(#iiXMpdd)"><path fill="url(#iSLX2md)" class="jl_xj-bhs"/></g><path fill="url(#ihzPHzG)" class="zjf6ysbmv"/><path fill="url(#iT5I5Mc)" class="zjf6ysbmv"/><path fill="url(#ihMnqmc)" class="zjf6ysbmv"/><path fill="url(#iLcnPie)" class="egj5m-b0v"/><path fill="url(#il9Ybea)" class="ls--enbcf"/><path fill="url(#ibSPSBe)" class="m2rlewbuf"/><path fill="url(#iLjckee)" class="nhjkfywfr"/><path fill="url(#i5TIjed)" class="ziu2vzb_h"/><path fill="url(#iGmC3Ge)" class="mc9yhabks"/><path fill="url(#ijRffXd)" class="xzls5xmto"/><g filter="url(#ibsO1Id)"><path class="ji4d0efdq"/></g><g filter="url(#iZgVOWp)"><path stroke="url(#iLI63wc)" class="l7d4ozbeh"/></g><g filter="url(#ik51esV)"><path class="q6iitcaou"/></g><defs><linearGradient id="iYfu29b" x1="21.441" x2="13.565" y1="5.502" y2="5.502" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset=".456" class="kmmuo7biq"/><stop offset="1" class="c3htxbc9y"/></linearGradient><linearGradient id="iYQ9QZs" x1="17.963" x2="17.963" y1="7.422" y2="6.672" gradientUnits="userSpaceOnUse"><stop class="qyc8_3a8l"/><stop offset="1" class="x_4saz8rv"/></linearGradient><linearGradient id="it7jZMc" x1="15.978" x2="15.978" y1="30.688" y2="27.75" gradientUnits="userSpaceOnUse"><stop class="opisyab6y"/><stop offset="1" class="h71410fpg"/></linearGradient><linearGradient id="i9deNiH" x1="24.666" x2="24.666" y1="1.125" y2="6.063" gradientUnits="userSpaceOnUse"><stop class="ci0km3bwi"/><stop offset="1" class="lv-1skbvu"/></linearGradient><linearGradient id="iSLX2md" x1="25.183" x2="8.527" y1="4.594" y2="4.594" gradientUnits="userSpaceOnUse"><stop class="oygd70yps"/><stop offset="1" class="ct7qqxbfx"/></linearGradient><linearGradient id="ihzPHzG" x1="24.022" x2="23.393" y1="4.887" y2="4.887" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="iT5I5Mc" x1="24.192" x2="24.192" y1="5.936" y2="4.966" gradientUnits="userSpaceOnUse"><stop class="vh3k8hojv"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iLcnPie" x1="4.666" x2="1.976" y1="16.42" y2="16.42" gradientUnits="userSpaceOnUse"><stop class="xer1mrb1c"/><stop offset="1" class="njlbmxb8c"/></linearGradient><linearGradient id="il9Ybea" x1="3.353" x2="5.385" y1="11.344" y2="12.719" gradientUnits="userSpaceOnUse"><stop class="aa6460bno"/><stop offset="1" class="yepff4yau"/></linearGradient><linearGradient id="ibSPSBe" x1="6.666" x2="8.041" y1="7.969" y2="10.128" gradientUnits="userSpaceOnUse"><stop class="lylh85old"/><stop offset="1" class="mj32zksqy"/></linearGradient><linearGradient id="iLjckee" x1="11.466" x2="11.468" y1="6.459" y2="9" gradientUnits="userSpaceOnUse"><stop class="ptciclbtt"/><stop offset="1" class="r00d7-j0a"/></linearGradient><linearGradient id="i5TIjed" x1="27.354" x2="30.197" y1="17.244" y2="17.244" gradientUnits="userSpaceOnUse"><stop class="aeqieey7g"/><stop offset="1" class="r_k1cgbrg"/></linearGradient><linearGradient id="iGmC3Ge" x1="27.356" x2="30.186" y1="13.004" y2="13.004" gradientUnits="userSpaceOnUse"><stop class="aeqieey7g"/><stop offset="1" class="r_k1cgbrg"/></linearGradient><linearGradient id="ijRffXd" x1="27.359" x2="30.175" y1="9.004" y2="9.004" gradientUnits="userSpaceOnUse"><stop class="aeqieey7g"/><stop offset="1" class="r_k1cgbrg"/></linearGradient><linearGradient id="iLI63wc" x1="28.084" x2="19.238" y1="26.878" y2="26.878" gradientUnits="userSpaceOnUse"><stop class="c71gu0bic"/><stop offset="1" class="yd65j_xbw"/></linearGradient><radialGradient id="iBKD34c" cx="0" cy="0" r="1" gradientTransform="matrix(-.51563 .95312 -2.07943 -1.12495 18.478 5.687)" gradientUnits="userSpaceOnUse"><stop class="qyc8_3a8l"/><stop offset="1" class="x_4saz8rv"/></radialGradient><radialGradient id="i5nVH7b" cx="0" cy="0" r="1" gradientTransform="rotate(124.745 7.467 9.362)scale(22.5905 29.2009)" gradientUnits="userSpaceOnUse"><stop offset=".854" class="h71410fpg"/><stop offset="1" class="opisyab6y"/></radialGradient><radialGradient id="iZQ1f2c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.8125 .5625 -1.22961 -8.33395 8.978 19.313)" gradientUnits="userSpaceOnUse"><stop class="ci0km3bwi"/><stop offset="1" class="lv-1skbvu"/></radialGradient><radialGradient id="ildjWtd" cx="0" cy="0" r="1" gradientTransform="matrix(-.3125 2.6875 -7.2465 -.84261 15.04 23.75)" gradientUnits="userSpaceOnUse"><stop class="ci0km3bwi"/><stop offset="1" class="lv-1skbvu"/></radialGradient><radialGradient id="iTt1EYc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.87501 2.24997 -2.765 -4.762 30.478 27)" gradientUnits="userSpaceOnUse"><stop class="vmldx61od"/><stop offset="1" class="qpuln9bhi"/></radialGradient><radialGradient id="iSKnkLb" cx="0" cy="0" r="1" gradientTransform="rotate(130.067 14.393 8.26)scale(6.41094 6.51774)" gradientUnits="userSpaceOnUse"><stop class="xazc1g3-i"/><stop offset="1" class="n-amz253s"/></radialGradient><radialGradient id="iySEB3i" cx="0" cy="0" r="1" gradientTransform="matrix(-3.4375 2.4375 -3.76246 -5.30606 21.103 11.563)" gradientUnits="userSpaceOnUse"><stop class="ci0km3bwi"/><stop offset="1" class="lv-1skbvu"/></radialGradient><radialGradient id="iIZvByc" cx="0" cy="0" r="1" gradientTransform="rotate(114.117 2.619 10.726)scale(5.88903 6.22369)" gradientUnits="userSpaceOnUse"><stop class="e6bs32pao"/><stop offset=".957" class="e-oy9ubfe"/></radialGradient><radialGradient id="iEiZiwc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03122 4.06251 -4.58293 -1.16332 12.103 14.031)" gradientUnits="userSpaceOnUse"><stop class="opisyab6y"/><stop offset=".957" class="h71410fpg"/></radialGradient><radialGradient id="iphpjhT" cx="0" cy="0" r="1" gradientTransform="matrix(-3.375 .9375 -.564 -2.03042 22.697 8.594)" gradientUnits="userSpaceOnUse"><stop class="opisyab6y"/><stop offset=".957" class="h71410fpg"/></radialGradient><radialGradient id="i7NnORc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.28125 4.65625 0 23.416 18.563)" gradientUnits="userSpaceOnUse"><stop class="znc2d8brq"/><stop offset="1" class="rvb55zbzf"/></radialGradient><radialGradient id="ijDpHwb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40625 0 0 -6.84375 25.01 14.344)" gradientUnits="userSpaceOnUse"><stop class="znc2d8brq"/><stop offset="1" class="rvb55zbzf"/></radialGradient><radialGradient id="i4kpRqe" cx="0" cy="0" r="1" gradientTransform="rotate(-47.632 18.523 -17.722)scale(3.84895 8.24874)" gradientUnits="userSpaceOnUse"><stop class="g4329fbnd"/><stop offset="1" class="r6biiabrn"/></radialGradient><radialGradient id="ihMnqmc" cx="0" cy="0" r="1" gradientTransform="rotate(-105.735 13.757 -6.346)scale(1.19614 1.35865)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="zmzak_sfz"/><stop offset="1" class="dyysy0bzo"/></radialGradient><filter id="iiXMpdd" width="12.498" height="4.875" x="16.822" y="1.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5567" stdDeviation=".75"/></filter><filter id="ibsO1Id" width="22.196" height="21.75" x="2.674" y="7.628" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5567" stdDeviation="1"/></filter><filter id="iZgVOWp" width="13.109" height="4.872" x="17.245" y="25.378" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5567" stdDeviation=".5"/></filter><filter id="ik51esV" width="19.125" height="22.269" x="11.603" y="1.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5567" stdDeviation="1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:snake" /></template>
<style>
.aa6460bno {
  stop-color: var(--svg-color--a9be3c, #A9BE3C);
}

.aeqieey7g {
  stop-color: var(--svg-color--c8df4f, #C8DF4F);
}

.c3htxbc9y {
  stop-color: var(--svg-color--ec098c, #EC098C);
}

.c71gu0bic {
  stop-color: var(--svg-color--5fdba4, #5FDBA4);
}

.ci0km3bwi {
  stop-color: var(--svg-color--57d493, #57D493);
}

.ct7qqxbfx {
  stop-color: var(--svg-color--47d38d, #47D38D);
  stop-opacity: 0;
}

.dyysy0bzo {
  stop-color: var(--svg-color--594c4f, #594C4F);
}

.e-oy9ubfe {
  stop-color: var(--svg-color--43b096, #43B096);
  stop-opacity: 0;
}

.e6bs32pao {
  stop-color: var(--svg-color--43b096, #43B096);
}

.egj5m-b0v {
  d: path("M4.038 16.42c0-.55-.45-1-1-1h-1q-.075.645-.06 1.29c0 .24.02.47.03.71h1.03c.56 0 1-.45 1-1");
}

.ft5dv1b6b {
  fill: none;
}

.g_zp97ben {
  d: path("M29.768 28.39a8.7 8.7 0 0 0-6.91-3.41h-5.24c-3.22 0-5.9-.75-7.76-2.18c-1.9-1.46-2.87-3.62-2.87-6.43c0-2.46 2.01-4.45 4.47-4.43c2.42.02 4.44 2.02 4.47 4.44v.54c0 2.24 1.03 4.37 2.83 5.7c1.18.87 2.62 1.38 4.18 1.38c3.88 0 7.04-3.16 7.04-7.04l-.04-12.15c0-1.55-1.26-2.81-2.82-2.81h-9.56c-.35 0-.63.28-.62.63c0 2.97 2.4 5.37 5.37 5.37h2.3c.17 0 .31.14.31.31l.04 8.65c0 1.1-.88 1.99-1.98 2.02c-1.13.03-2.05-.91-2.05-2.04v-.74c-.09-5.13-4.37-9.27-9.52-9.27c-5.32 0-9.53 4.46-9.43 9.78c.08 4.23 1.75 7.7 4.82 10.07c2.75 2.11 6.48 3.22 10.82 3.22h11.36c.83 0 1.3-.95.79-1.61");
}

.g4329fbnd {
  stop-color: var(--svg-color--41a591, #41A591);
}

.h71410fpg {
  stop-color: var(--svg-color--8596da, #8596DA);
  stop-opacity: 0;
}

.ji4d0efdq {
  stroke: var(--svg-color--57e0a3, #57E0A3);
  stroke-linecap: round;
  d: path("M11.182 10.128c-1.562 0-6.5.75-5.969 6.937c.532 6.188 4.36 8.279 8.922 9.247c2.543.54 6.391.566 8.235.566");
}

.jl_xj-bhs {
  d: path("M21.326 4.594c-1.605 0-2.558-.892-2.97-1.546c-.095-.15.022-.33.2-.33h9.015a.25.25 0 0 1 .25.25v1.376a.25.25 0 0 1-.25.25z");
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.kmmuo7biq {
  stop-color: var(--svg-color--ed1452, #ED1452);
}

.l7d4ozbeh {
  stroke-linecap: round;
  d: path("M28.853 28.75c-.75-.666-3.463-1.872-5.978-1.872h-4.13");
}

.ls--enbcf {
  d: path("m4.668 11.34l-.86-.5c-.39.54-.72 1.12-1 1.73l.86.5c.48.28 1.09.11 1.37-.37a.99.99 0 0 0-.37-1.36");
}

.lv-1skbvu {
  stop-color: var(--svg-color--57d493, #57D493);
  stop-opacity: 0;
}

.lylh85old {
  stop-color: var(--svg-color--b0ca47, #B0CA47);
}

.m2rlewbuf {
  d: path("M7.758 9.99c.48-.28.64-.89.37-1.37l-.52-.88c-.61.28-1.19.62-1.73 1.01l.51.88c.28.48.89.64 1.37.36");
}

.mc9yhabks {
  d: path("M29.959 12h-1.03c-.55 0-1 .45-1 1s.45 1 1 1h1.04z");
}

.mj32zksqy {
  stop-color: var(--svg-color--b5c637, #B5C637);
}

.n-amz253s {
  stop-color: var(--svg-color--64e69a, #64E69A);
  stop-opacity: 0;
}

.nhjkfywfr {
  d: path("M10.468 6.98V8c0 .55.45 1 1 1s1-.45 1-1V6.99a9.2 9.2 0 0 0-2-.01");
}

.njlbmxb8c {
  stop-color: var(--svg-color--a9b63e, #A9B63E);
}

.opisyab6y {
  stop-color: var(--svg-color--8596da, #8596DA);
}

.oygd70yps {
  stop-color: var(--svg-color--47d38d, #47D38D);
}

.ptciclbtt {
  stop-color: var(--svg-color--b2ce45, #B2CE45);
}

.q6iitcaou {
  stroke: var(--svg-color--50e69b, #50E69B);
  stroke-linecap: round;
  d: path("M14.104 9.188c1.729.208 5.187 1.874 5.187 7.25c0 4.75 3.14 5.453 5.047 5.234s3.89-1.485 3.89-5.922V4.438");
}

.qpuln9bhi {
  stop-color: var(--svg-color--59d993, #59D993);
  stop-opacity: 0;
}

.qyc8_3a8l {
  stop-color: var(--svg-color--813c31, #813C31);
}

.r_k1cgbrg {
  stop-color: var(--svg-color--cfe54c, #CFE54C);
}

.r00d7-j0a {
  stop-color: var(--svg-color--bdcf42, #BDCF42);
}

.r6biiabrn {
  stop-color: var(--svg-color--41a591, #41A591);
  stop-opacity: 0;
}

.rvb55zbzf {
  stop-color: var(--svg-color--3cb373, #3CB373);
  stop-opacity: 0;
}

.u6_e1kz0i {
  stop-color: var(--svg-color--392833, #392833);
}

.vh3k8hojv {
  stop-color: var(--svg-color--492847, #492847);
}

.vmldx61od {
  stop-color: var(--svg-color--59d993, #59D993);
}

.vq76pqe1z {
  stop-color: var(--svg-color--ed1c26, #ED1C26);
}

.wcsuz9b-d {
  fill: var(--svg-color--46ba9a, #46BA9A);
  d: path("M29.768 28.39a8.7 8.7 0 0 0-6.91-3.41h-5.24c-3.22 0-5.9-.75-7.76-2.18c-1.9-1.46-2.87-3.62-2.87-6.43c0-2.46 2.01-4.45 4.47-4.43c2.42.02 4.44 2.02 4.47 4.44v.54c0 2.24 1.03 4.37 2.83 5.7c1.18.87 2.62 1.38 4.18 1.38c3.88 0 7.04-3.16 7.04-7.04l-.04-12.15c0-1.55-1.26-2.81-2.82-2.81h-9.56c-.35 0-.63.28-.62.63c0 2.97 2.4 5.37 5.37 5.37h2.3c.17 0 .31.14.31.31l.04 8.65c0 1.1-.88 1.99-1.98 2.02c-1.13.03-2.05-.91-2.05-2.04v-.74c-.09-5.13-4.37-9.27-9.52-9.27c-5.32 0-9.53 4.46-9.43 9.78c.08 4.23 1.75 7.7 4.82 10.07c2.75 2.11 6.48 3.22 10.82 3.22h11.36c.83 0 1.3-.95.79-1.61");
}

.x_4saz8rv {
  stop-color: var(--svg-color--813c31, #813C31);
  stop-opacity: 0;
}

.xazc1g3-i {
  stop-color: var(--svg-color--64e69a, #64E69A);
}

.xer1mrb1c {
  stop-color: var(--svg-color--b4bb3d, #B4BB3D);
}

.xzls5xmto {
  d: path("M29.949 8h-1.02c-.55 0-1 .45-1 1s.45 1 1 1h1.03z");
}

.yd65j_xbw {
  stop-color: var(--svg-color--5fdba4, #5FDBA4);
  stop-opacity: 0;
}

.yepff4yau {
  stop-color: var(--svg-color--b1be36, #B1BE36);
}

.z6co97pbh {
  d: path("M19.558 6c-1.4 0-2.75-.61-3.64-1.7c-.03-.04-.06-.07-.09-.11a.5.5 0 0 0-.71-.08c-.21.17-.24.49-.07.71c.35.45.76.85 1.21 1.18h-.81c-.27 0-.5.2-.52.47c-.01.29.22.53.51.53h6V6z");
}

.ziu2vzb_h {
  d: path("M27.929 17.24c0 .55.45 1 1 1h.93c.08-.41.12-.84.12-1.28v-.72h-1.05c-.55 0-1 .45-1 1");
}

.zjf6ysbmv {
  d: path("M23.48 6.031a.547.547 0 0 1-.544-.543V4.54c0-.297.246-.543.543-.543s.543.246.543.543v.948a.54.54 0 0 1-.543.543");
}

.zmzak_sfz {
  stop-color: var(--svg-color--594c4f, #594C4F);
  stop-opacity: 0;
}

.znc2d8brq {
  stop-color: var(--svg-color--3cb373, #3CB373);
}

</style>
