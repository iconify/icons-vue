<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ihUsX6d)" class="q13zxjdap"/><path fill="url(#iqgyxRc)" class="q13zxjdap"/><path fill="url(#iQ3fccd)" class="q13zxjdap"/><path class="r08n0-byr"/><path fill="url(#i7QS0id)" class="d9wog7jwa"/><path fill="url(#i8Gepad)" class="d9wog7jwa"/><path fill="url(#iis9kxd)" class="d9wog7jwa"/><g filter="url(#izVvcde)"><rect fill="url(#iur89Zd)" class="vtl4xrb8v"/></g><path fill="url(#inTNtjc)" class="wkk7ejmmq"/><path fill="url(#iMgKdnB)" class="t5z2m4j_t"/><path fill="url(#iwVKDcv)" class="m-6redcom"/><path fill="url(#iO2VXcb)" class="xan41yb5b"/><path fill="url(#ihQEeyb)" class="d4r_-_b-n"/><path fill="url(#i1igB5b)" class="wo_q68vvj"/><path fill="url(#iWoQkKe)" class="m74ez2bwq"/><path fill="url(#iyicz0c)" class="bw2mm8y1b"/><path fill="url(#iIV7Anu)" class="n6aiczbgc"/><path fill="url(#i0WFR1b)" class="vzur_2b0z"/><path fill="url(#iCzNkze)" class="r6x-lou0y"/><path fill="url(#iEhGkEc)" class="r6x-lou0y"/><path fill="url(#idza0Ge)" class="l25syrbpx"/><path fill="url(#i8sx6Cd)" class="jwdr273gf"/><path fill="url(#iPI3bxA)" class="jwdr273gf"/><path fill="url(#i1lOLge)" class="i09p05ebf"/><path fill="url(#ixDOQae)" class="eqax2-wcl"/><g filter="url(#iKaOA1H)"><path fill="url(#iFA5wad)" class="fycijkbxl"/></g><g filter="url(#i7wRuPd)"><path fill="url(#ikRRNeu)" class="fycijkbxl"/></g><g filter="url(#izELHJe)"><path class="mjxms2r5j"/></g><g filter="url(#i7lpL8d)"><path class="vs6i0w_1e"/></g><defs><linearGradient id="ihUsX6d" x1="15.947" x2="15.947" y1="26.061" y2=".464" gradientUnits="userSpaceOnUse"><stop class="nl2orebih"/><stop offset="1" class="dzca75iiv"/></linearGradient><linearGradient id="iqgyxRc" x1="-1.783" x2="5.247" y1="20.315" y2="20.315" gradientUnits="userSpaceOnUse"><stop class="rcgbucecq"/><stop offset="1" class="o1u7ztjhk"/></linearGradient><linearGradient id="iQ3fccd" x1="17.127" x2="17.127" y1="31.59" y2="27.281" gradientUnits="userSpaceOnUse"><stop offset=".127" class="pic8qkb9r"/><stop offset="1" class="siq704zhl"/></linearGradient><linearGradient id="i7QS0id" x1="6.993" x2="7.724" y1="23.722" y2="24.475" gradientUnits="userSpaceOnUse"><stop class="vq1-yfbzr"/><stop offset="1" class="th4w_j2pb"/></linearGradient><linearGradient id="iur89Zd" x1="27.108" x2="27.108" y1="4.156" y2="26.717" gradientUnits="userSpaceOnUse"><stop class="kw9odfpmw"/><stop offset="1" class="wh-x3498z"/></linearGradient><linearGradient id="iMgKdnB" x1="9.383" x2="8.844" y1="9.259" y2="9.831" gradientUnits="userSpaceOnUse"><stop class="gppqfbb_s"/><stop offset="1" class="w59ruo60p"/></linearGradient><linearGradient id="iO2VXcb" x1="6.403" x2="6.403" y1="16.087" y2="16.977" gradientUnits="userSpaceOnUse"><stop class="w3k9ucq1b"/><stop offset="1" class="xjmg0ubye"/></linearGradient><linearGradient id="iWoQkKe" x1="16.548" x2="15.831" y1="26.493" y2="26.493" gradientUnits="userSpaceOnUse"><stop class="khfy9foji"/><stop offset="1" class="sjfmrzbpo"/></linearGradient><linearGradient id="iIV7Anu" x1="22.845" x2="22.285" y1="22.829" y2="23.356" gradientUnits="userSpaceOnUse"><stop class="dky2pnb6p"/><stop offset="1" class="t21irg3_k"/></linearGradient><linearGradient id="iEhGkEc" x1="25.713" x2="25.713" y1="17.171" y2="16.532" gradientUnits="userSpaceOnUse"><stop class="sv52hebws"/><stop offset="1" class="qv_p7db4q"/></linearGradient><linearGradient id="iPI3bxA" x1="21.057" x2="22.853" y1="11.734" y2="9.787" gradientUnits="userSpaceOnUse"><stop class="sv52hebws"/><stop offset="1" class="qv_p7db4q"/></linearGradient><linearGradient id="ixDOQae" x1="16.249" x2="15.586" y1="7.355" y2="7.355" gradientUnits="userSpaceOnUse"><stop class="si527db8p"/><stop offset="1" class="qbdbxg_fl"/></linearGradient><linearGradient id="iFA5wad" x1="21.087" x2="12.932" y1="14.724" y2="19.733" gradientUnits="userSpaceOnUse"><stop offset=".291" class="w6xhxacgk"/><stop offset="1" class="of0ky0l0n"/></linearGradient><linearGradient id="ikRRNeu" x1="20.023" x2="10.139" y1="16.547" y2="20.707" gradientUnits="userSpaceOnUse"><stop offset=".21" class="qrid5_b9c"/><stop offset="1" class="of0ky0l0n"/></linearGradient><radialGradient id="i8Gepad" cx="0" cy="0" r="1" gradientTransform="rotate(132.898 -.215 14.337)scale(7.69983 2.55926)" gradientUnits="userSpaceOnUse"><stop class="js62ocbws"/><stop offset="1" class="spvng-mub"/></radialGradient><radialGradient id="iis9kxd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37396 6.24911 -1.93452 -.42533 13.552 18.979)" gradientUnits="userSpaceOnUse"><stop class="n1r8axb0r"/><stop offset="1" class="tigiajbzp"/></radialGradient><radialGradient id="inTNtjc" cx="0" cy="0" r="1" gradientTransform="matrix(-.53036 .56157 -.56156 -.53036 11.788 7.313)" gradientUnits="userSpaceOnUse"><stop class="vtspxcb2v"/><stop offset="1" class="p6y1jcbva"/></radialGradient><radialGradient id="iwVKDcv" cx="0" cy="0" r="1" gradientTransform="matrix(-.53037 .56156 -.56155 -.53037 6.788 12.313)" gradientUnits="userSpaceOnUse"><stop class="k58zbdbcs"/><stop offset="1" class="nvp8x5byw"/></radialGradient><radialGradient id="ihQEeyb" cx="0" cy="0" r="1" gradientTransform="matrix(-.53037 .56156 -.56155 -.53037 6.788 20.313)" gradientUnits="userSpaceOnUse"><stop class="k58zbdbcs"/><stop offset="1" class="nvp8x5byw"/></radialGradient><radialGradient id="i1igB5b" cx="0" cy="0" r="1" gradientTransform="matrix(-.53036 .56157 -.56156 -.53036 12.767 25.313)" gradientUnits="userSpaceOnUse"><stop class="arjw6nbaa"/><stop offset="1" class="gueoa_gmi"/></radialGradient><radialGradient id="iyicz0c" cx="0" cy="0" r="1" gradientTransform="matrix(-.53039 .56156 -.56155 -.53039 19.788 25.313)" gradientUnits="userSpaceOnUse"><stop class="fxry_sv_t"/><stop offset="1" class="sd05am3ze"/></radialGradient><radialGradient id="i0WFR1b" cx="0" cy="0" r="1" gradientTransform="matrix(-.53037 .56156 -.56155 -.53037 25.788 20.313)" gradientUnits="userSpaceOnUse"><stop class="tqki1x7wb"/><stop offset="1" class="y4_8unbts"/></radialGradient><radialGradient id="iCzNkze" cx="0" cy="0" r="1" gradientTransform="matrix(-1.60249 0 0 -.45834 27.628 16.532)" gradientUnits="userSpaceOnUse"><stop class="m0fiaacha"/><stop offset="1" class="cr57gbc8g"/></radialGradient><radialGradient id="idza0Ge" cx="0" cy="0" r="1" gradientTransform="matrix(-.53037 .56156 -.56155 -.53037 25.818 12.313)" gradientUnits="userSpaceOnUse"><stop class="u0d6o0udw"/><stop offset="1" class="mszj1mbis"/></radialGradient><radialGradient id="i8sx6Cd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1406 2.32814 -.66383 -.61036 24.51 7.89)" gradientUnits="userSpaceOnUse"><stop class="m0fiaacha"/><stop offset="1" class="cr57gbc8g"/></radialGradient><radialGradient id="i1lOLge" cx="0" cy="0" r="1" gradientTransform="matrix(-.53037 .56156 -.56155 -.53037 20.788 7.313)" gradientUnits="userSpaceOnUse"><stop class="y31w9jfhe"/><stop offset="1" class="t4jgcfbla"/></radialGradient><filter id="izVvcde" width="7.055" height="27.561" x="23.58" y="1.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_372" stdDeviation="1.25"/></filter><filter id="iKaOA1H" width="15.144" height="14.844" x="8.215" y="9.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.905882 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_372"/></filter><filter id="i7wRuPd" width="15.094" height="15.094" x="8.515" y="8.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.501961 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_372"/></filter><filter id="izELHJe" width="5.425" height="4.297" x="18.237" y="15.807" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_372" stdDeviation=".3"/></filter><filter id="i7lpL8d" width="2.444" height="6.162" x="17.05" y="9.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_372" stdDeviation=".3"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:sparkler" /></template>
<style>
.arjw6nbaa {
  stop-color: var(--svg-color--ffbd55, #FFBD55);
}

.bw2mm8y1b {
  d: path("M19.963 25.515a.5.5 0 1 1-1 0a.5.5 0 0 1 1 0");
}

.cr57gbc8g {
  stop-color: var(--svg-color--ffcf32, #FFCF32);
}

.d4r_-_b-n {
  d: path("M6.463 21.015a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.d9wog7jwa {
  d: path("m13.393 17.832l-10.69 10.69c.34.46.79.83 1.3 1.09l10.59-10.59z");
}

.dky2pnb6p {
  stop-color: var(--svg-color--ffe25b, #FFE25B);
}

.dzca75iiv {
  stop-color: var(--svg-color--1c1c1d, #1C1C1D);
}

.eqax2-wcl {
  d: path("M16.398 5.302a.445.445 0 0 0-.89 0v3.38a.445.445 0 1 0 .89 0z");
}

.ft5dv1b6b {
  fill: none;
}

.fxry_sv_t {
  stop-color: var(--svg-color--ffd556, #FFD556);
}

.fycijkbxl {
  d: path("m22.943 13.282l-4.25.91c-.24.06-.45-.16-.4-.4l.91-4.25c.08-.37-.41-.58-.62-.26l-2.36 3.65c-.13.21-.44.21-.57 0l-2.36-3.65c-.21-.31-.7-.11-.62.26l.91 4.25c.06.24-.16.45-.4.4l-4.25-.91c-.37-.08-.58.41-.26.62l3.65 2.36c.21.13.21.44 0 .57l-3.65 2.36c-.31.21-.11.7.26.62l4.25-.91c.24-.06.45.16.4.4l-.91 4.25c-.08.37.41.58.62.26l2.36-3.65c.13-.21.44-.21.57 0l2.36 3.65c.21.31.7.11.62-.26l-.91-4.25c-.06-.24.16-.45.4-.4l4.25.91c.37.08.58-.41.26-.62l-3.65-2.36a.337.337 0 0 1 0-.57l3.65-2.36c.31-.21.11-.7-.26-.62");
}

.gppqfbb_s {
  stop-color: var(--svg-color--ffc059, #FFC059);
}

.gueoa_gmi {
  stop-color: var(--svg-color--ff964f, #FF964F);
}

.i09p05ebf {
  d: path("M20.963 7.515a.5.5 0 1 1-1 0a.5.5 0 0 1 1 0");
}

.js62ocbws {
  stop-color: var(--svg-color--dfc7f6, #DFC7F6);
}

.jwdr273gf {
  d: path("M24.208 8.277a.445.445 0 0 1 0 .63l-2.39 2.39a.445.445 0 1 1-.63-.63l2.39-2.39a.445.445 0 0 1 .63 0");
}

.k58zbdbcs {
  stop-color: var(--svg-color--ffb052, #FFB052);
}

.khfy9foji {
  stop-color: var(--svg-color--ffc953, #FFC953);
}

.kw9odfpmw {
  stop-color: var(--svg-color--514e55, #514E55);
}

.l25syrbpx {
  d: path("M25.993 12.515a.5.5 0 1 1-1 0a.5.5 0 0 1 1 0");
}

.m-6redcom {
  d: path("M6.463 13.015a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.m0fiaacha {
  stop-color: var(--svg-color--ffed61, #FFED61);
}

.m74ez2bwq {
  d: path("M15.953 23.947c.245 0 .445.2.445.445v3.38a.445.445 0 0 1-.89 0v-3.38c0-.246.199-.445.445-.445");
}

.mjxms2r5j {
  stroke: var(--svg-color--ffe557, #FFE557);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.975 16.532c-.039.109-.008.4.423.692c.43.293 2.539 1.558 3.539 2.154");
}

.mszj1mbis {
  stop-color: var(--svg-color--ffc744, #FFC744);
}

.n1r8axb0r {
  stop-color: var(--svg-color--c79cb8, #C79CB8);
}

.n6aiczbgc {
  d: path("M21.188 21.777a.445.445 0 0 1 .63 0l2.39 2.39a.445.445 0 1 1-.63.63l-2.39-2.39a.445.445 0 0 1 0-.63");
}

.nl2orebih {
  stop-color: var(--svg-color--8a52b9, #8A52B9);
}

.nvp8x5byw {
  stop-color: var(--svg-color--fa8a3d, #FA8A3D);
}

.o1u7ztjhk {
  stop-color: var(--svg-color--5e2e91, #5E2E91);
  stop-opacity: 0;
}

.of0ky0l0n {
  stop-color: var(--svg-color--ec9744, #EC9744);
}

.p6y1jcbva {
  stop-color: var(--svg-color--fc9b32, #FC9B32);
}

.pic8qkb9r {
  stop-color: var(--svg-color--5d328d, #5D328D);
}

.q13zxjdap {
  d: path("M26.253 2.015H5.643c-2.03 0-3.68 1.65-3.68 3.68v20.61c0 2.03 1.65 3.68 3.68 3.68h20.61c2.03 0 3.68-1.65 3.68-3.68V5.695c0-2.03-1.64-3.68-3.68-3.68");
}

.qbdbxg_fl {
  stop-color: var(--svg-color--eca132, #ECA132);
}

.qrid5_b9c {
  stop-color: var(--svg-color--ec9744, #EC9744);
  stop-opacity: 0;
}

.qv_p7db4q {
  stop-color: var(--svg-color--f0b258, #F0B258);
  stop-opacity: 0;
}

.r08n0-byr {
  fill: var(--svg-color--cab1e3, #CAB1E3);
  d: path("m13.393 17.832l-10.69 10.69c.34.46.79.83 1.3 1.09l10.59-10.59z");
}

.r6x-lou0y {
  d: path("M23.358 16.532c0-.246.199-.445.444-.445h3.38a.445.445 0 1 1 0 .89h-3.38a.445.445 0 0 1-.444-.445");
}

.rcgbucecq {
  stop-color: var(--svg-color--181818, #181818);
}

.sd05am3ze {
  stop-color: var(--svg-color--ffae4e, #FFAE4E);
}

.si527db8p {
  stop-color: var(--svg-color--ffd257, #FFD257);
}

.siq704zhl {
  stop-color: var(--svg-color--5d328d, #5D328D);
  stop-opacity: 0;
}

.sjfmrzbpo {
  stop-color: var(--svg-color--faa249, #FAA249);
}

.spvng-mub {
  stop-color: var(--svg-color--dfc7f6, #DFC7F6);
  stop-opacity: 0;
}

.sv52hebws {
  stop-color: var(--svg-color--f0b258, #F0B258);
}

.t21irg3_k {
  stop-color: var(--svg-color--ffbe52, #FFBE52);
}

.t4jgcfbla {
  stop-color: var(--svg-color--ffb737, #FFB737);
}

.t5z2m4j_t {
  d: path("M8.318 8.277a.445.445 0 1 0-.63.63l2.39 2.39a.445.445 0 1 0 .63-.63z");
}

.th4w_j2pb {
  stop-color: var(--svg-color--a594b1, #A594B1);
  stop-opacity: 0;
}

.tigiajbzp {
  stop-color: var(--svg-color--c79cb8, #C79CB8);
  stop-opacity: 0;
}

.tqki1x7wb {
  stop-color: var(--svg-color--ffeb5f, #FFEB5F);
}

.u0d6o0udw {
  stop-color: var(--svg-color--ffec61, #FFEC61);
}

.vq1-yfbzr {
  stop-color: var(--svg-color--a594b1, #A594B1);
}

.vs6i0w_1e {
  stroke: var(--svg-color--ffe557, #FFE557);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m18.77 9.778l-.982 4.232a.403.403 0 0 0 .25.48");
}

.vtl4xrb8v {
  width: 2.055px;
  height: 22.561px;
  x: 26.08px;
  y: 4.156px;
  rx: 1.027px;
}

.vtspxcb2v {
  stop-color: var(--svg-color--ffc255, #FFC255);
}

.vzur_2b0z {
  d: path("M25.963 20.515a.5.5 0 1 1-1 0a.5.5 0 0 1 1 0");
}

.w3k9ucq1b {
  stop-color: var(--svg-color--f59c43, #F59C43);
}

.w59ruo60p {
  stop-color: var(--svg-color--fb9634, #FB9634);
}

.w6xhxacgk {
  stop-color: var(--svg-color--ffcf50, #FFCF50);
}

.wh-x3498z {
  stop-color: var(--svg-color--9f6ad1, #9F6AD1);
}

.wkk7ejmmq {
  d: path("M11.963 7.515a.5.5 0 1 1-1 0a.5.5 0 0 1 1 0");
}

.wo_q68vvj {
  d: path("M12.443 26.015a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.xan41yb5b {
  d: path("M4.713 16.087a.445.445 0 1 0 0 .89h3.38a.445.445 0 1 0 0-.89z");
}

.xjmg0ubye {
  stop-color: var(--svg-color--ed8242, #ED8242);
}

.y31w9jfhe {
  stop-color: var(--svg-color--ffdc5c, #FFDC5C);
}

.y4_8unbts {
  stop-color: var(--svg-color--ffc23e, #FFC23E);
}

</style>
