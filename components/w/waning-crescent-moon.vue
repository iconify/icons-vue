<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#iF8hr1Y)" class="lmh4whbrs"/><circle fill="url(#iMGz34p)" class="lmh4whbrs"/><circle fill="url(#iXDjjHc)" class="lmh4whbrs"/><circle fill="url(#i3q69JN)" class="lmh4whbrs"/><circle fill="url(#iDfclyq)" class="x5_7l-bbi"/><circle fill="url(#iWAy2He)" class="g4k3q7cmw"/><circle fill="url(#isY3BBc)" class="h2-o4in6u"/><g filter="url(#iYF1Gab)"><circle stroke="url(#iWmCMLb)" class="aif3dxb6p"/></g><path fill="url(#iDSx0Vz)" class="lf_xyqbww"/><path fill="url(#iK72nye)" class="lf_xyqbww"/><path fill="url(#iJvur2b)" class="cmiujyb_i"/><path fill="url(#iZO5kub)" class="grr143byi"/><path fill="url(#iKin6rd)" class="grr143byi"/><g filter="url(#ihgbD4c)"><circle fill="url(#ihdA4bc)" class="g4k3q7cmw"/><circle stroke="url(#i2pnNjJ)" class="xrwbo5xlm"/></g><circle fill="url(#isN18QL)" class="h2-o4in6u"/><g filter="url(#iNMSKOc)"><circle stroke="url(#iYnGicd)" class="m34e9s3yo"/></g><circle fill="url(#iKWPu0b)" class="h2-o4in6u"/><circle fill="url(#ii89wLe)" class="h2-o4in6u"/><circle fill="url(#iSzeb0c)" class="h2-o4in6u"/><circle fill="url(#i5OsGie)" class="h2-o4in6u"/><circle fill="url(#i00DHBC)" class="az0fwjbyp"/><circle fill="url(#iaNIHcc)" class="az0fwjbyp"/><circle fill="url(#iLSfHyb)" class="az0fwjbyp"/><g filter="url(#iP6K0ne)"><path stroke="url(#iZEA6Sc)" class="pbc8zfb0o"/></g><path fill="url(#iQsdB1b)" class="cmiujyb_i"/><path fill="url(#iJIDgkc)" class="cmiujyb_i"/><path fill="url(#iSzvL0d)" class="cmiujyb_i"/><g filter="url(#inGqt9b)"><path stroke="url(#iGtnAub)" class="vx_6jij2g"/></g><path fill="url(#iCqtVBb)" class="os0xi4bfi"/><g filter="url(#iy3ACRe)"><ellipse fill="url(#ihA1tUd)" class="prk6f8-6b"/><ellipse fill="url(#iAVTFjA)" class="prk6f8-6b"/><path stroke="url(#i0XI7ge)" class="lm-t3ya8g"/></g><defs><radialGradient id="iF8hr1Y" cx="0" cy="0" r="1" gradientTransform="rotate(133.363 8.703 9.384)scale(24.7588)" gradientUnits="userSpaceOnUse"><stop class="ifsoepbvs"/><stop offset="1" class="gap-yf33v"/></radialGradient><radialGradient id="iMGz34p" cx="0" cy="0" r="1" gradientTransform="matrix(.38605 19.97867 -22.83274 .4412 12.492 8.506)" gradientUnits="userSpaceOnUse"><stop class="lwtiepbsd"/><stop offset="1" class="qd_ykob0j"/></radialGradient><radialGradient id="iXDjjHc" cx="0" cy="0" r="1" gradientTransform="rotate(-168.07 8.836 7.164)scale(14.3091 29.0338)" gradientUnits="userSpaceOnUse"><stop offset=".6" class="tn8znfqhp"/><stop offset=".91" class="z26pzunsr"/></radialGradient><radialGradient id="i3q69JN" cx="0" cy="0" r="1" gradientTransform="rotate(-32.811 41.724 5.974)scale(8.72756)" gradientUnits="userSpaceOnUse"><stop class="uba9r9z3v"/><stop offset="1" class="yit1cyesw"/></radialGradient><radialGradient id="iK72nye" cx="0" cy="0" r="1" gradientTransform="rotate(-142.952 9.324 11.92)scale(5.57176 3.36972)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="te8heeq8v"/><stop offset="1" class="uu4-6olre"/></radialGradient><radialGradient id="iZO5kub" cx="0" cy="0" r="1" gradientTransform="rotate(124.824 9.012 11.963)scale(18.85 17.2968)" gradientUnits="userSpaceOnUse"><stop class="hw2b6x7dh"/><stop offset=".815" class="b87g7p5kz"/></radialGradient><radialGradient id="iKin6rd" cx="0" cy="0" r="1" gradientTransform="matrix(-21.21512 9.36406 -13.30043 -30.13332 28.34 11.924)" gradientUnits="userSpaceOnUse"><stop offset=".52" class="i342g3_-x"/><stop offset="1" class="w9s4wq0bz"/></radialGradient><radialGradient id="ihdA4bc" cx="0" cy="0" r="1" gradientTransform="matrix(6.91643 -5.39316 1.77476 2.27603 20 13.396)" gradientUnits="userSpaceOnUse"><stop offset=".2" class="wecidrbdj"/><stop offset="1" class="j9bg4_aho"/></radialGradient><radialGradient id="iKWPu0b" cx="0" cy="0" r="1" gradientTransform="matrix(2.29671 -3.78 4.40069 2.67384 15.472 23.51)" gradientUnits="userSpaceOnUse"><stop class="nmqja-b5r"/><stop offset="1" class="mf987ss-p"/></radialGradient><radialGradient id="ii89wLe" cx="0" cy="0" r="1" gradientTransform="rotate(118.54 2.158 15.508)scale(3.1046 3.20092)" gradientUnits="userSpaceOnUse"><stop offset=".789" class="xhmqgdkdw"/><stop offset="1" class="od20u6b3v"/></radialGradient><radialGradient id="iSzeb0c" cx="0" cy="0" r="1" gradientTransform="matrix(3.52289 -4.27779 2.99635 2.46758 14.67 23.642)" gradientUnits="userSpaceOnUse"><stop offset=".8" class="hcvo9rclz"/><stop offset="1" class="aouzsrgog"/></radialGradient><radialGradient id="i5OsGie" cx="0" cy="0" r="1" gradientTransform="matrix(2.94774 2.48038 -2.63083 3.12654 15.676 20.873)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="kowu5e5ac"/><stop offset="1" class="sk_-w8f9q"/></radialGradient><radialGradient id="i00DHBC" cx="0" cy="0" r="1" gradientTransform="rotate(-47.175 20.864 -.52)scale(6.98771)" gradientUnits="userSpaceOnUse"><stop class="t8mzg_bgw"/><stop offset="1" class="asif75bjf"/></radialGradient><radialGradient id="iaNIHcc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.07919 0 0 -3.91074 10.08 12.5)" gradientUnits="userSpaceOnUse"><stop offset=".894" class="nppyrbc0j"/><stop offset="1" class="na16txwvj"/></radialGradient><radialGradient id="iLSfHyb" cx="0" cy="0" r="1" gradientTransform="matrix(5.375 -5.4375 4.05278 4.0062 6.813 15.136)" gradientUnits="userSpaceOnUse"><stop offset=".636" class="y2dt9rtuc"/><stop offset="1" class="tzxv8fgey"/></radialGradient><radialGradient id="iSzvL0d" cx="0" cy="0" r="1" gradientTransform="matrix(-.0625 -4.28125 5.84388 -.08531 27.279 25.1)" gradientUnits="userSpaceOnUse"><stop offset=".777" class="hyszpbcik"/><stop offset=".992" class="a6o3g7zqv"/></radialGradient><radialGradient id="iCqtVBb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.50004 4.40623 -2.55733 -1.451 12.5 11.35)" gradientUnits="userSpaceOnUse"><stop class="t2bobdbys"/><stop offset="1" class="ygb_3dbbs"/></radialGradient><radialGradient id="ihA1tUd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.51084 0 0 -2.73027 17.127 5.5)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="yuoatmb7a"/><stop offset="1" class="ar4v0iy4a"/></radialGradient><radialGradient id="iAVTFjA" cx="0" cy="0" r="1" gradientTransform="matrix(2.14598 0 0 1.88931 15.558 5.5)" gradientUnits="userSpaceOnUse"><stop offset=".711" class="pspj-mbwr"/><stop offset="1" class="x12ziqbrn"/></radialGradient><linearGradient id="iDfclyq" x1="16.5" x2="14.5" y1="4.5" y2="6.5" gradientUnits="userSpaceOnUse"><stop class="s334l8uyu"/><stop offset="1" class="nec_isxbo"/></linearGradient><linearGradient id="iWAy2He" x1="24.167" x2="20.833" y1="9.833" y2="13.167" gradientUnits="userSpaceOnUse"><stop class="s334l8uyu"/><stop offset="1" class="nec_isxbo"/></linearGradient><linearGradient id="isY3BBc" x1="18.167" x2="14.833" y1="19.833" y2="23.167" gradientUnits="userSpaceOnUse"><stop class="s334l8uyu"/><stop offset="1" class="nec_isxbo"/></linearGradient><linearGradient id="iWmCMLb" x1="11.325" x2="6.934" y1="9.361" y2="15.057" gradientUnits="userSpaceOnUse"><stop class="xe1h3_e7t"/><stop offset="1" class="nt99fmbml"/></linearGradient><linearGradient id="iDSx0Vz" x1="10.307" x2="5.964" y1="24.331" y2="26.993" gradientUnits="userSpaceOnUse"><stop class="zt28h012e"/><stop offset="1" class="bslbvcb-m"/></linearGradient><linearGradient id="iJvur2b" x1="29.833" x2="25.167" y1="22.167" y2="26.833" gradientUnits="userSpaceOnUse"><stop class="tfh0wfbse"/><stop offset="1" class="oc3sqsbox"/></linearGradient><linearGradient id="i2pnNjJ" x1="20.577" x2="23.646" y1="9" y2="14" gradientUnits="userSpaceOnUse"><stop class="co70-uzsf"/><stop offset=".492" class="ei1k3obco"/><stop offset="1" class="co70-uzsf"/></linearGradient><linearGradient id="isN18QL" x1="18.167" x2="14.833" y1="19.833" y2="23.167" gradientUnits="userSpaceOnUse"><stop class="odmjt405d"/><stop offset="1" class="qf2998b3n"/></linearGradient><linearGradient id="iYnGicd" x1="19" x2="14.409" y1="19.675" y2="23.332" gradientUnits="userSpaceOnUse"><stop class="v0xcpxbum"/><stop offset="1" class="l90x68blj"/></linearGradient><linearGradient id="iZEA6Sc" x1="27.338" x2="24.231" y1="20.781" y2="26.152" gradientUnits="userSpaceOnUse"><stop class="z2mp41bxm"/><stop offset=".999" class="ot4-jgt4j"/></linearGradient><linearGradient id="iQsdB1b" x1="29.833" x2="25.167" y1="22.167" y2="26.833" gradientUnits="userSpaceOnUse"><stop class="odmjt405d"/><stop offset="1" class="qf2998b3n"/></linearGradient><linearGradient id="iJIDgkc" x1="25.873" x2="27.06" y1="25.975" y2="19.787" gradientUnits="userSpaceOnUse"><stop class="g4rfypbmn"/><stop offset="1" class="o-kypwb8c"/></linearGradient><linearGradient id="iGtnAub" x1="13.5" x2="10.797" y1="13.007" y2="12.928" gradientUnits="userSpaceOnUse"><stop class="z0b87_bvb"/><stop offset="1" class="o1-l35x6g"/></linearGradient><linearGradient id="i0XI7ge" x1="17.35" x2="14.761" y1="4.297" y2="6.843" gradientUnits="userSpaceOnUse"><stop class="cweie4cnk"/><stop offset="1" class="v05dmuh-v"/></linearGradient><filter id="iYF1Gab" width="7.8" height="7.8" x="5.6" y="8.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14055" stdDeviation=".15"/></filter><filter id="ihgbD4c" width="5.8" height="5.8" x="19.6" y="8.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14055" stdDeviation=".1"/></filter><filter id="iNMSKOc" width="5.75" height="5.75" x="13.625" y="18.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14055" stdDeviation=".125"/></filter><filter id="iP6K0ne" width="5.591" height="6.505" x="23.653" y="20.498" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14055" stdDeviation=".15"/></filter><filter id="inGqt9b" width="12.114" height="15.089" x="4.986" y="5.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14055" stdDeviation="2"/></filter><filter id="iy3ACRe" width="4.008" height="3.6" x="13.996" y="3.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14055" stdDeviation=".1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:waning-crescent-moon" /></template>
<style>
.a6o3g7zqv {
  stop-color: var(--svg-color--663f8e, #663F8E);
}

.aif3dxb6p {
  cx: 9.5px;
  cy: 12.5px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.aouzsrgog {
  stop-color: var(--svg-color--64398c, #64398C);
}

.ar4v0iy4a {
  stop-color: var(--svg-color--a276c9, #A276C9);
}

.asif75bjf {
  stop-color: var(--svg-color--d5a04b, #D5A04B);
}

.az0fwjbyp {
  cx: 9.5px;
  cy: 12.5px;
  r: 3.5px;
}

.b87g7p5kz {
  stop-color: var(--svg-color--6f419e, #6F419E);
}

.bslbvcb-m {
  stop-color: var(--svg-color--ae6b71, #AE6B71);
}

.cmiujyb_i {
  d: path("M28.955 21.316a14.04 14.04 0 0 1-4.073 5.507a3.5 3.5 0 0 1 4.074-5.507");
}

.co70-uzsf {
  stop-color: var(--svg-color--a57cd3, #A57CD3);
}

.cweie4cnk {
  stop-color: var(--svg-color--7b52a5, #7B52A5);
}

.ei1k3obco {
  stop-color: var(--svg-color--a57cd3, #A57CD3);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g4k3q7cmw {
  cx: 22.5px;
  cy: 11.5px;
  r: 2.5px;
}

.g4rfypbmn {
  stop-color: var(--svg-color--8a60b5, #8A60B5);
}

.gap-yf33v {
  stop-color: var(--svg-color--f7ca32, #F7CA32);
}

.grr143byi {
  d: path("M15.681 29.996Q15.84 30 16 30c7.732 0 14-6.268 14-14S23.732 2 16 2q-.16 0-.32.004C11.606 5.304 9 10.348 9 16s2.605 10.697 6.681 13.996");
}

.h2-o4in6u {
  cx: 16.5px;
  cy: 21.5px;
  r: 2.5px;
}

.hcvo9rclz {
  stop-color: var(--svg-color--64398c, #64398C);
  stop-opacity: 0;
}

.hw2b6x7dh {
  stop-color: var(--svg-color--9f76cc, #9F76CC);
}

.hyszpbcik {
  stop-color: var(--svg-color--663f8e, #663F8E);
  stop-opacity: 0;
}

.i342g3_-x {
  stop-color: var(--svg-color--402d53, #402D53);
  stop-opacity: 0;
}

.ifsoepbvs {
  stop-color: var(--svg-color--feed6e, #FEED6E);
}

.j9bg4_aho {
  stop-color: var(--svg-color--8e61b7, #8E61B7);
}

.kowu5e5ac {
  stop-color: var(--svg-color--664289, #664289);
  stop-opacity: 0;
}

.l90x68blj {
  stop-color: var(--svg-color--683b92, #683B92);
  stop-opacity: 0;
}

.lf_xyqbww {
  d: path("M10.189 28.74a14.05 14.05 0 0 1-5.439-4.405a3.5 3.5 0 1 1 5.439 4.406");
}

.lm-t3ya8g {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16 7.05c.962 0 1.754-.688 1.754-1.55S16.962 3.95 16 3.95c-.963 0-1.754.688-1.754 1.55S15.037 7.05 16 7.05Z");
}

.lmh4whbrs {
  cx: 16px;
  cy: 16px;
  r: 14px;
}

.lwtiepbsd {
  stop-color: var(--svg-color--fac26f, #FAC26F);
}

.m34e9s3yo {
  cx: 16.5px;
  cy: 21.5px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
}

.mf987ss-p {
  stop-color: var(--svg-color--6f4197, #6F4197);
}

.na16txwvj {
  stop-color: var(--svg-color--ffc553, #FFC553);
}

.nec_isxbo {
  stop-color: var(--svg-color--ffef71, #FFEF71);
}

.nmqja-b5r {
  stop-color: var(--svg-color--724d94, #724D94);
}

.nppyrbc0j {
  stop-color: var(--svg-color--ffc553, #FFC553);
  stop-opacity: 0;
}

.nt99fmbml {
  stop-color: var(--svg-color--d79c38, #D79C38);
}

.o-kypwb8c {
  stop-color: var(--svg-color--885bb3, #885BB3);
}

.o1-l35x6g {
  stop-color: var(--svg-color--5f3e80, #5F3E80);
  stop-opacity: 0;
}

.oc3sqsbox {
  stop-color: var(--svg-color--fff073, #FFF073);
}

.od20u6b3v {
  stop-color: var(--svg-color--8b72a3, #8B72A3);
}

.odmjt405d {
  stop-color: var(--svg-color--0f0f0f, #0F0F0F);
}

.os0xi4bfi {
  d: path("M9 15.965c1.253-1.034 2.148-2.241 2.148-3.897c0-1.338-.387-2.466-.781-2.96A3.502 3.502 0 0 1 9 15.965");
}

.ot4-jgt4j {
  stop-color: var(--svg-color--7e55ac, #7E55AC);
}

.pbc8zfb0o {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M28.902 21.21a3.4 3.4 0 0 0-1.424-.312c-1.892 0-3.425 1.545-3.425 3.45c0 .879.326 1.68.863 2.29");
}

.prk6f8-6b {
  cx: 16px;
  cy: 5.5px;
  rx: 1.704px;
  ry: 1.5px;
}

.pspj-mbwr {
  stop-color: var(--svg-color--664581, #664581);
  stop-opacity: 0;
}

.qd_ykob0j {
  stop-color: var(--svg-color--cd7442, #CD7442);
}

.qf2998b3n {
  stop-color: var(--svg-color--704e8d, #704E8D);
}

.s334l8uyu {
  stop-color: var(--svg-color--f5c224, #F5C224);
}

.sk_-w8f9q {
  stop-color: var(--svg-color--664289, #664289);
}

.t2bobdbys {
  stop-color: var(--svg-color--614776, #614776);
}

.t8mzg_bgw {
  stop-color: var(--svg-color--f6b953, #F6B953);
}

.te8heeq8v {
  stop-color: var(--svg-color--af4c46, #AF4C46);
  stop-opacity: 0;
}

.tfh0wfbse {
  stop-color: var(--svg-color--f6c72d, #F6C72D);
}

.tn8znfqhp {
  stop-color: var(--svg-color--b28d55, #B28D55);
  stop-opacity: 0;
}

.tzxv8fgey {
  stop-color: var(--svg-color--bd8d44, #BD8D44);
}

.uba9r9z3v {
  stop-color: var(--svg-color--ad6648, #AD6648);
}

.uu4-6olre {
  stop-color: var(--svg-color--af4c46, #AF4C46);
}

.v05dmuh-v {
  stop-color: var(--svg-color--875cb4, #875CB4);
}

.v0xcpxbum {
  stop-color: var(--svg-color--683b92, #683B92);
}

.vx_6jij2g {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M9 15.965q.245.035.5.035a3.5 3.5 0 0 0 .867-6.892");
}

.w9s4wq0bz {
  stop-color: var(--svg-color--402d53, #402D53);
}

.wecidrbdj {
  stop-color: var(--svg-color--b085d8, #B085D8);
}

.x12ziqbrn {
  stop-color: var(--svg-color--664581, #664581);
}

.x5_7l-bbi {
  cx: 15.5px;
  cy: 5.5px;
  r: 1.5px;
}

.xe1h3_e7t {
  stop-color: var(--svg-color--e4ac50, #E4AC50);
}

.xhmqgdkdw {
  stop-color: var(--svg-color--8b72a3, #8B72A3);
  stop-opacity: 0;
}

.xrwbo5xlm {
  cx: 22.5px;
  cy: 11.5px;
  r: 2.6px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.y2dt9rtuc {
  stop-color: var(--svg-color--bd8d44, #BD8D44);
  stop-opacity: 0;
}

.ygb_3dbbs {
  stop-color: var(--svg-color--62427c, #62427C);
}

.yit1cyesw {
  stop-color: var(--svg-color--ad6648, #AD6648);
  stop-opacity: 0;
}

.yuoatmb7a {
  stop-color: var(--svg-color--79529b, #79529B);
}

.z0b87_bvb {
  stop-color: var(--svg-color--5f3e80, #5F3E80);
}

.z26pzunsr {
  stop-color: var(--svg-color--b08647, #B08647);
}

.z2mp41bxm {
  stop-color: var(--svg-color--7246a2, #7246A2);
}

.zt28h012e {
  stop-color: var(--svg-color--bd6152, #BD6152);
}

</style>
