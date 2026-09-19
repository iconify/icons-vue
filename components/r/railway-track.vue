<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ilswIBd)"><path fill="url(#iTa333c)" class="ijzn3-hqc"/></g><g filter="url(#iAFD1xd)"><rect stroke="url(#iPon80c)" class="z422aebau"/></g><g filter="url(#iEVZbkb)"><path fill="url(#i29lGhc)" class="lk65eyfaa"/><path fill="url(#ir2o46b)" class="lk65eyfaa"/><path fill="url(#iXJSKFb)" class="lk65eyfaa"/></g><path fill="url(#i1nJsEd)" class="hgzbpnbwm"/><path fill="url(#i4PoViH)" class="hgzbpnbwm"/><g filter="url(#iwE7X1d)"><path class="ecjd0ixct"/></g><g filter="url(#izztvkc)"><path class="jlsgomdkx"/></g><g filter="url(#iH8MOHb)"><path class="h15u_r6kz"/></g><path fill="url(#izmIHBa)" class="gfl9umbox"/><path fill="url(#iLhxs2c)" class="licn80w_e"/><path fill="url(#iJEnzhe)" class="r3l0u41zh"/><rect fill="url(#iZWK3vd)" class="j2d7-wbat"/><path fill="url(#i1rGkwb)" class="h0pem_bvn"/><path fill="url(#iWZ4wtd)" class="qh4ajubwb"/><path fill="url(#iiXDkAe)" class="jz5hvccop"/><g filter="url(#iCqrKkb)"><path fill="url(#ikQrnwd)" class="wri1xwj9l"/></g><g filter="url(#ijNYNYc)"><path fill="url(#izks5ac)" class="ez5dv3bii"/></g><path fill="url(#iFykPJb)" class="btzqd6bns"/><path fill="url(#iXnUTjd)" class="zvq1jbcxg"/><path fill="url(#imT8Oqd)" class="e2jm_jbdg"/><path fill="url(#ibcJo9c)" class="l1i-1ccol"/><defs><linearGradient id="iTa333c" x1="16.02" x2="16.02" y1="2.017" y2="17.281" gradientUnits="userSpaceOnUse"><stop class="qvczd9_ix"/><stop offset="1" class="lcknh5n5s"/></linearGradient><linearGradient id="iPon80c" x1="5.221" x2="27.953" y1="17" y2="1.344" gradientUnits="userSpaceOnUse"><stop class="z-6pdccut"/><stop offset="1" class="dojenzbwu"/></linearGradient><linearGradient id="i29lGhc" x1="16.458" x2="16.453" y1="27.688" y2="10" gradientUnits="userSpaceOnUse"><stop class="l3wc3hbvc"/><stop offset="1" class="yillusb5m"/></linearGradient><linearGradient id="i1nJsEd" x1="16" x2="16" y1="16.214" y2="25.094" gradientUnits="userSpaceOnUse"><stop class="xuiz77k4d"/><stop offset="1" class="z5j_r91pv"/></linearGradient><linearGradient id="i4PoViH" x1="24.739" x2="19.989" y1="24.125" y2="26.281" gradientUnits="userSpaceOnUse"><stop class="ezhwyzekg"/><stop offset="1" class="jvvl5vbau"/></linearGradient><linearGradient id="izmIHBa" x1="25.428" x2="6.578" y1="23.505" y2="23.505" gradientUnits="userSpaceOnUse"><stop class="uid_4-bee"/><stop offset="1" class="hlonkzbio"/></linearGradient><linearGradient id="iLhxs2c" x1="21.231" x2="10.814" y1="19.003" y2="19.003" gradientUnits="userSpaceOnUse"><stop class="uid_4-bee"/><stop offset="1" class="hlonkzbio"/></linearGradient><linearGradient id="iJEnzhe" x1="16.044" x2="18.805" y1="16.375" y2="16.375" gradientUnits="userSpaceOnUse"><stop class="udn55bbhk"/><stop offset="1" class="po2-ugvfl"/></linearGradient><linearGradient id="iZWK3vd" x1="13.76" x2="16.809" y1="16.916" y2="16.916" gradientUnits="userSpaceOnUse"><stop class="z5pu2ybbl"/><stop offset="1" class="pakpoxbfv"/></linearGradient><linearGradient id="i1rGkwb" x1="23.958" x2="1.708" y1="27.5" y2="30" gradientUnits="userSpaceOnUse"><stop class="iobztlb-d"/><stop offset="1" class="qo8trvv3l"/></linearGradient><linearGradient id="iWZ4wtd" x1="6.518" x2="23.02" y1="24.502" y2="24.502" gradientUnits="userSpaceOnUse"><stop class="zagvd-bqu"/><stop offset="1" class="p_6aumbfq"/></linearGradient><linearGradient id="iiXDkAe" x1="10.814" x2="21.231" y1="19.662" y2="19.662" gradientUnits="userSpaceOnUse"><stop class="ce792pb8s"/><stop offset="1" class="joo_vzluh"/></linearGradient><linearGradient id="ikQrnwd" x1="17.114" x2="25.239" y1="16.625" y2="29.375" gradientUnits="userSpaceOnUse"><stop class="n7t2gj3zi"/><stop offset=".714" class="n7t2gj3zi"/><stop offset="1" class="vhte_3bib"/></linearGradient><linearGradient id="izks5ac" x1="14.239" x2="5.364" y1="17" y2="28.563" gradientUnits="userSpaceOnUse"><stop offset=".797" class="n7t2gj3zi"/><stop offset="1" class="cl2oxuavl"/></linearGradient><linearGradient id="iFykPJb" x1="6.36" x2="15.804" y1="30" y2="14.717" gradientUnits="userSpaceOnUse"><stop class="n4ulyckbj"/><stop offset="1" class="y-g_vioux"/></linearGradient><linearGradient id="iXnUTjd" x1="15.67" x2="5.615" y1="16" y2="30.011" gradientUnits="userSpaceOnUse"><stop class="upu-okbkm"/><stop offset="1" class="idb5spbnh"/></linearGradient><linearGradient id="imT8Oqd" x1="25.458" x2="16.853" y1="29.313" y2="15.987" gradientUnits="userSpaceOnUse"><stop class="l3pxlomup"/><stop offset="1" class="y-g_vioux"/><stop offset="1" class="dn8cms7wd"/></linearGradient><linearGradient id="ibcJo9c" x1="16.643" x2="26.275" y1="16" y2="30" gradientUnits="userSpaceOnUse"><stop class="it3f_9zqt"/><stop offset="1" class="gjp7_kb5o"/></linearGradient><filter id="ilswIBd" width="28" height="15.983" x="2.02" y="2.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.670588 0 0 0 0 0.890196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11793"/></filter><filter id="iAFD1xd" width="27.907" height="27.907" x="2.047" y="2.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11793" stdDeviation="1"/></filter><filter id="iEVZbkb" width="28" height="18.75" x="2.02" y="12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.941176 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11793"/></filter><filter id="iwE7X1d" width="19.203" height="3.604" x="6.458" y="22.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11793" stdDeviation=".25"/></filter><filter id="izztvkc" width="10.547" height="1.754" x="10.786" y="18.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11793" stdDeviation=".125"/></filter><filter id="iH8MOHb" width="5.672" height="1.146" x="13.223" y="16.177" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11793" stdDeviation=".125"/></filter><filter id="iCqrKkb" width="10.425" height="14.188" x="16.064" y="15.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11793" stdDeviation=".125"/></filter><filter id="ijNYNYc" width="10.994" height="14.188" x="4.823" y="15.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11793" stdDeviation=".125"/></filter><radialGradient id="ir2o46b" cx="0" cy="0" r="1" gradientTransform="rotate(122.495 12.667 13.618)scale(11.6339 18.0972)" gradientUnits="userSpaceOnUse"><stop class="zigjd0tzz"/><stop offset="1" class="jp1z366ac"/></radialGradient><radialGradient id="iXJSKFb" cx="0" cy="0" r="1" gradientTransform="rotate(51.756 -5.535 5.815)scale(16.1546 25.1294)" gradientUnits="userSpaceOnUse"><stop class="zigjd0tzz"/><stop offset="1" class="jp1z366ac"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:railway-track" /></template>
<style>
.btzqd6bns {
  d: path("M6.52 30h-1l9.69-14h.61z");
}

.ce792pb8s {
  stop-color: var(--svg-color--99665f, #99665F);
}

.cl2oxuavl {
  stop-color: var(--svg-color--6a4540, #6A4540);
}

.dn8cms7wd {
  stop-color: var(--svg-color--6c567a, #6C567A);
}

.dojenzbwu {
  stop-color: var(--svg-color--4cecff, #4CECFF);
  stop-opacity: 0;
}

.e2jm_jbdg {
  d: path("M25.56 30h1l-9.65-14h-.62z");
}

.ecjd0ixct {
  fill: var(--svg-color--271935, #271935);
  d: path("M25.161 24.927c0 .233-.471.26-.726.26H7.58c-.255 0-.623-.1-.623-.342c0-.233.047-.208.227-.39l1.512-1.688c.155-.143.299-.183.509-.183h13.78c.187 0 .368.054.479.19l1.453 1.752c.17.19.243.167.243.4");
}

.ez5dv3bii {
  d: path("M6.073 29.828h-1l9.874-13.687h.62z");
}

.ezhwyzekg {
  stop-color: var(--svg-color--4f435b, #4F435B);
}

.ft5dv1b6b {
  fill: none;
}

.gfl9umbox {
  d: path("M25.169 24.7c0 .268.032.3-.239.3H7.08c-.27 0-.228-.116-.228-.395c0-.269-.38-.24-.19-.449l1.6-1.945c.165-.164.317-.211.54-.211h14.593c.2 0 .391.063.508.219l1.54 2.02c.18.218-.274.191-.274.46");
}

.gjp7_kb5o {
  stop-color: var(--svg-color--978ca2, #978CA2);
}

.h0pem_bvn {
  d: path("m29.18 28.584l-1.058-1.208a1.24 1.24 0 0 0-.819-.376H4.887c-.28 0-.649.158-.839.366l-1.168 1.24A3.8 3.8 0 0 0 5.82 30h20.4a3.8 3.8 0 0 0 2.96-1.416");
}

.h15u_r6kz {
  fill: var(--svg-color--271935, #271935);
  d: path("M18.645 17.008c0 .058-.133.065-.206.065H13.65c-.072 0-.177-.025-.177-.085c0-.058.014-.052.065-.097l.43-.418a.2.2 0 0 1 .144-.046h3.915c.054 0 .105.014.136.047l.413.435c.049.047.07.041.07.099");
}

.hgzbpnbwm {
  d: path("M14.734 16.3a8 8 0 0 1-.794-.025L3.243 28.992a3.8 3.8 0 0 0 2.097.978H26.7a3.8 3.8 0 0 0 2.057-.94L18.085 16.213c-.61.09-1.284.141-2.04.141q-.699 0-1.312-.055");
}

.hlonkzbio {
  stop-color: var(--svg-color--6a4532, #6A4532);
}

.idb5spbnh {
  stop-color: var(--svg-color--998fa4, #998FA4);
}

.ijzn3-hqc {
  d: path("M5.82 2.017a3.8 3.8 0 0 0-3.8 3.8V18h28V5.817a3.8 3.8 0 0 0-3.8-3.8z");
}

.iobztlb-d {
  stop-color: var(--svg-color--7c5652, #7C5652);
}

.it3f_9zqt {
  stop-color: var(--svg-color--bbb1c5, #BBB1C5);
}

.j2d7-wbat {
  width: 5.582px;
  height: 0.316px;
  x: 13.25px;
  y: 16.684px;
  rx: 0.158px;
}

.jlsgomdkx {
  fill: var(--svg-color--271935, #271935);
  d: path("M21.083 20.004c0 .112-.26.126-.4.126H11.38c-.141 0-.344-.049-.344-.165c0-.113.026-.1.125-.188l.835-.813a.4.4 0 0 1 .28-.088h7.606c.104 0 .204.026.265.091l.802.844c.094.092.134.08.134.193");
}

.joo_vzluh {
  stop-color: var(--svg-color--74504e, #74504E);
}

.jp1z366ac {
  stop-color: var(--svg-color--39ed7a, #39ED7A);
  stop-opacity: 0;
}

.jvvl5vbau {
  stop-color: var(--svg-color--4f435b, #4F435B);
  stop-opacity: 0;
}

.jz5hvccop {
  d: path("M21.23 19.66c0-.184-.127-.339-.397-.339h-9.61c-.27 0-.413.155-.413.34s.133.339.413.339h9.61c.28 0 .397-.154.397-.34");
}

.l1i-1ccol {
  d: path("M27.003 29.92L17.06 16h-.62l9.62 14h.16q.404-.001.783-.08");
}

.l3pxlomup {
  stop-color: var(--svg-color--62516d, #62516D);
}

.l3wc3hbvc {
  stop-color: var(--svg-color--286a54, #286A54);
}

.lcknh5n5s {
  stop-color: var(--svg-color--2df9ff, #2DF9FF);
}

.licn80w_e {
  d: path("M21.23 19.67c0 .18-.23.33-.5.33h-9.42c-.27 0-.286-.07-.286-.25s-.172.039-.172-.25l1.063-1.383c.066-.094.187-.117.273-.117h7.617c.165 0 .274.043.36.145l.98 1.289c.18.22-.093.236.085.236");
}

.lk65eyfaa {
  d: path("M2.02 12.003V26.2a3.8 3.8 0 0 0 3.8 3.8h20.4a3.8 3.8 0 0 0 3.8-3.796V12c-3.494.005-5.24 1.093-6.984 2.18c-1.747 1.088-3.492 2.175-6.99 2.175s-5.259-1.088-7.019-2.177C7.27 13.09 5.51 12.003 2.02 12.003");
}

.n4ulyckbj {
  stop-color: var(--svg-color--93839e, #93839E);
}

.n7t2gj3zi {
  stop-color: var(--svg-color--2e203b, #2E203B);
}

.p_6aumbfq {
  stop-color: var(--svg-color--76514f, #76514F);
}

.pakpoxbfv {
  stop-color: var(--svg-color--72504d, #72504D);
}

.po2-ugvfl {
  stop-color: var(--svg-color--996960, #996960);
}

.qh4ajubwb {
  d: path("M25.52 24.5a.51.51 0 0 0-.504-.5H7.024a.503.503 0 0 0-.504.5c0 .27.232.5.504.5h17.992c.273 0 .504-.22.504-.5");
}

.qo8trvv3l {
  stop-color: var(--svg-color--a16c62, #A16C62);
}

.qvczd9_ix {
  stop-color: var(--svg-color--35c9ff, #35C9FF);
}

.r3l0u41zh {
  d: path("m13.863 16.07l-.58.68h5.522l-.604-.683a.2.2 0 0 0-.15-.067h-4.036a.2.2 0 0 0-.152.07");
}

.udn55bbhk {
  stop-color: var(--svg-color--795650, #795650);
}

.uid_4-bee {
  stop-color: var(--svg-color--a2694f, #A2694F);
}

.upu-okbkm {
  stop-color: var(--svg-color--beb5c9, #BEB5C9);
}

.vhte_3bib {
  stop-color: var(--svg-color--523135, #523135);
}

.wri1xwj9l {
  d: path("M25.349 29.828h.89l-9.304-13.687h-.62z");
}

.xuiz77k4d {
  stop-color: var(--svg-color--352a41, #352A41);
}

.y-g_vioux {
  stop-color: var(--svg-color--887d8f, #887D8F);
}

.yillusb5m {
  stop-color: var(--svg-color--3bde75, #3BDE75);
}

.z-6pdccut {
  stop-color: var(--svg-color--4cecff, #4CECFF);
}

.z422aebau {
  width: 22.907px;
  height: 22.907px;
  x: 4.547px;
  y: 4.547px;
  rx: 1.5px;
}

.z5j_r91pv {
  stop-color: var(--svg-color--392c46, #392C46);
}

.z5pu2ybbl {
  stop-color: var(--svg-color--98665e, #98665E);
}

.zagvd-bqu {
  stop-color: var(--svg-color--a06861, #A06861);
}

.zigjd0tzz {
  stop-color: var(--svg-color--39ed7a, #39ED7A);
}

.zvq1jbcxg {
  d: path("m6.02 30l9.65-14h-.61L5.073 29.927q.364.072.747.073z");
}

</style>
