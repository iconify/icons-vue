<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iYc6u0c)"><path fill="url(#iCAC15b)" class="v2u7938xt"/></g><path fill="url(#iw0eiNd)" class="v2u7938xt"/><path class="wuo5gfbdq"/><path fill="url(#isX0Pwd)" class="o_c6xze2t"/><path class="u-atv7afl"/><g filter="url(#ixfsYCb)"><circle transform="rotate(28.149 23.688 9.952)" class="ffbbwvmyl"/></g><path stroke="url(#ir8fsJc)" class="z3x9-tb2n"/><path stroke="url(#iJrl6Ne)" class="tgyqa-2it"/><circle fill="url(#i8tzRwy)" class="q7zrt5s0u"/><circle fill="url(#iiQCMWM)" class="yc0-1ibos"/><circle fill="url(#iCWCBMb)" class="d-gwkrz9p"/><g filter="url(#iqK6WJc)"><path class="cmq6wpb5a"/></g><path class="u-ob932te"/><path stroke="url(#iSpQLjc)" class="nrv6g7ctl"/><path stroke="url(#iwxdENs)" class="nrv6g7ctl"/><path stroke="url(#iWuMzDb)" class="nrv6g7ctl"/><g filter="url(#ijKo6Cd)"><path class="wvqg5ii8l"/></g><g filter="url(#iVICvTP)"><circle class="k8ls25bfg"/></g><path fill="url(#ipDUBbc)" class="dg5rncg3i"/><g filter="url(#imspyjb)"><path stroke="url(#icwUVvd)" class="f32rn3poh"/></g><path stroke="url(#ilZzZQc)" class="ztk3tpbxf"/><g filter="url(#irjaq8d)"><path stroke="url(#iQTc3Cd)" class="h6rhh9bdc"/></g><path stroke="url(#im0EMNe)" class="nb9v5ub1k"/><defs><radialGradient id="iCAC15b" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.338 10.168)scale(34.8273)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iw0eiNd" cx="0" cy="0" r="1" gradientTransform="rotate(90 1.625 14.376)scale(16.6092)" gradientUnits="userSpaceOnUse"><stop offset=".824" class="og2_-db3e"/><stop offset="1" class="iedbks3oi"/></radialGradient><radialGradient id="ir8fsJc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.07814 -2.48437 10.52297 -8.80232 27.89 8.914)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="g8b11actz"/><stop offset=".854" class="h13dd1l8r"/><stop offset="1" class="ffzx5qb6k"/></radialGradient><radialGradient id="iJrl6Ne" cx="0" cy="0" r="1" gradientTransform="matrix(-2.07814 -2.48437 10.52297 -8.80232 9.89 27.914)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="g8b11actz"/><stop offset=".854" class="h13dd1l8r"/><stop offset="1" class="ffzx5qb6k"/></radialGradient><radialGradient id="i8tzRwy" cx="0" cy="0" r="1" gradientTransform="matrix(-1 1 -1 -1 26.5 27.5)" gradientUnits="userSpaceOnUse"><stop class="euu0wtbbi"/><stop offset="1" class="jsbk_hbmd"/></radialGradient><radialGradient id="iiQCMWM" cx="0" cy="0" r="1" gradientTransform="matrix(-1 1 -1 -1 9.5 19.5)" gradientUnits="userSpaceOnUse"><stop class="euu0wtbbi"/><stop offset="1" class="jsbk_hbmd"/></radialGradient><radialGradient id="iCWCBMb" cx="0" cy="0" r="1" gradientTransform="matrix(-1 1 -1 -1 24.5 2.5)" gradientUnits="userSpaceOnUse"><stop class="euu0wtbbi"/><stop offset="1" class="jsbk_hbmd"/></radialGradient><radialGradient id="iSpQLjc" cx="0" cy="0" r="1" gradientTransform="matrix(4.59375 .78125 -1.32293 7.77884 21.438 15.32)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="da37anbth"/><stop offset="1" class="m9sc6f8qz"/></radialGradient><radialGradient id="iwxdENs" cx="0" cy="0" r="1" gradientTransform="matrix(1.0625 .5625 -.80992 1.52985 26.188 16.055)" gradientUnits="userSpaceOnUse"><stop class="da37anbth"/><stop offset="1" class="m9sc6f8qz"/></radialGradient><radialGradient id="iWuMzDb" cx="0" cy="0" r="1" gradientTransform="matrix(-.21875 -4.3125 17.74559 -.90013 27.781 22.008)" gradientUnits="userSpaceOnUse"><stop class="da37anbth"/><stop offset=".602" class="m9sc6f8qz"/></radialGradient><radialGradient id="ipDUBbc" cx="0" cy="0" r="1" gradientTransform="matrix(5.92629 0 0 6.45766 17 19.83)" gradientUnits="userSpaceOnUse"><stop class="dya7igbyb"/><stop offset=".4" class="lwn7d2bir"/><stop offset=".676" class="h03jjx7le"/></radialGradient><radialGradient id="icwUVvd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.86733 2.94335 -5.0929 -3.23105 22.072 12.094)" gradientUnits="userSpaceOnUse"><stop class="e58ypubby"/><stop offset=".634" class="kpj5w9bmw"/></radialGradient><radialGradient id="ilZzZQc" cx="0" cy="0" r="1" gradientTransform="matrix(-.1749 -6.53686 9.16333 -.24518 20.98 13.213)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="ccr58nbuz"/><stop offset=".276" class="gvfj_gdms"/><stop offset=".401" class="ovz69fb_x"/></radialGradient><radialGradient id="iQTc3Cd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.86733 2.94335 -5.0929 -3.23105 12.69 12.09)" gradientUnits="userSpaceOnUse"><stop class="e58ypubby"/><stop offset=".634" class="kpj5w9bmw"/></radialGradient><radialGradient id="im0EMNe" cx="0" cy="0" r="1" gradientTransform="matrix(-.1749 -6.53686 9.16333 -.24518 11.803 13.213)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="ccr58nbuz"/><stop offset=".276" class="gvfj_gdms"/><stop offset=".401" class="ovz69fb_x"/></radialGradient><filter id="iYc6u0c" width="28" height="28" x="3" y="1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2" dy="-2"/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.08 0"/><feBlend in2="shape" result="effect1_innerShadow_6810_5230"/></filter><filter id="ixfsYCb" width="6.203" height="6.203" x="20.587" y="6.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6810_5230" stdDeviation="1"/></filter><filter id="iqK6WJc" width="11.144" height="8.896" x="17.75" y="12.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6810_5230" stdDeviation=".5"/></filter><filter id="ijKo6Cd" width="13.405" height="8.586" x="17.116" y="12.354" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6810_5230" stdDeviation=".5"/></filter><filter id="iVICvTP" width="2.766" height="2.766" x="25.953" y="14.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6810_5230" stdDeviation=".5"/></filter><filter id="imspyjb" width="6.402" height="4.832" x="17.645" y="10.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6810_5230" stdDeviation=".25"/></filter><filter id="irjaq8d" width="6.402" height="4.832" x="8.262" y="10.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6810_5230" stdDeviation=".25"/></filter><linearGradient id="isX0Pwd" x1="3" x2="16" y1="18.945" y2="4.133" gradientUnits="userSpaceOnUse"><stop class="i97_rac7h"/><stop offset=".859" class="fd278pmxy"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:partying-face" /></template>
<style>
.ccr58nbuz {
  stop-color: var(--svg-color--482641, #482641);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.cmq6wpb5a {
  stroke: var(--svg-color--bb582b, #BB582B);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-opacity: 0.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.5 19.997h4.929a2.7 2.7 0 0 0 2.697-2.637l.017-.776a1.94 1.94 0 0 0-1.939-1.982v0a1.55 1.55 0 0 0-1.551 1.551v.873c0 .501.406.907.907.907v0a.907.907 0 0 0 .908-.907v-.284");
}

.d-gwkrz9p {
  cx: 24px;
  cy: 3px;
  r: 1px;
}

.da37anbth {
  stop-color: var(--svg-color--1b6ad1, #1B6AD1);
}

.dg5rncg3i {
  d: path("M18 16.24a1 1 0 1 0 0 2a.295.295 0 1 1 0 .59a1 1 0 0 0 0 2a.295.295 0 1 1 0 .592a1 1 0 1 0 0 2a2.295 2.295 0 0 0 1.895-3.591A2.295 2.295 0 0 0 18 16.24");
}

.dya7igbyb {
  stop-color: var(--svg-color--3e3537, #3E3537);
}

.e58ypubby {
  stop-color: var(--svg-color--ca7a1b, #CA7A1B);
}

.euu0wtbbi {
  stop-color: var(--svg-color--45c9ff, #45C9FF);
}

.f32rn3poh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.895 12.677s.55-1.493 1.951-1.226c1.815.345 1.951 2.299 1.951 2.299");
}

.fd278pmxy {
  stop-color: var(--svg-color--5092ff, #5092FF);
  stop-opacity: 0;
}

.ffbbwvmyl {
  cx: 23.688px;
  cy: 9.952px;
  r: 1.101px;
  fill: var(--svg-color--e37847, #E37847);
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
}

.ffzx5qb6k {
  stop-color: var(--svg-color--ce336e, #CE336E);
}

.ft5dv1b6b {
  fill: none;
}

.g8b11actz {
  stop-color: var(--svg-color--ff42b1, #FF42B1);
}

.gvfj_gdms {
  stop-color: var(--svg-color--503a4a, #503A4A);
}

.h03jjx7le {
  stop-color: var(--svg-color--6a5662, #6A5662);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.h6rhh9bdc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.512 12.672s.55-1.493 1.951-1.227c1.815.346 1.951 2.3 1.951 2.3");
}

.i97_rac7h {
  stop-color: var(--svg-color--5092ff, #5092FF);
}

.iedbks3oi {
  stop-color: var(--svg-color--ff63c4, #FF63C4);
}

.jsbk_hbmd {
  stop-color: var(--svg-color--3e80ff, #3E80FF);
}

.k8ls25bfg {
  cx: 27.336px;
  cy: 16px;
  r: 0.383px;
  fill: var(--svg-color--c7e8ff, #C7E8FF);
}

.kpj5w9bmw {
  stop-color: var(--svg-color--ca7a1b, #CA7A1B);
  stop-opacity: 0;
}

.lwn7d2bir {
  stop-color: var(--svg-color--442932, #442932);
}

.m9sc6f8qz {
  stop-color: var(--svg-color--2a80f0, #2A80F0);
  stop-opacity: 0;
}

.nb9v5ub1k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-8px, 1.8px);
  d: path("M9.47 13.06c.216-.548.766-1.641 2.33-1.641c1.507 0 2.105 1.093 2.335 1.64");
}

.nrv6g7ctl {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.648 19.83h7.854a3.043 3.043 0 0 0 3.042-2.956l.008-.29a2.76 2.76 0 0 0-2.761-2.84h-.062a2.147 2.147 0 0 0-2.148 2.148v.314c0 .716.58 1.297 1.297 1.297v0c.716 0 1.296-.58 1.296-1.297v-.047");
}

.o_c6xze2t {
  d: path("M5 3h12L3 16V5a2 2 0 0 1 2-2");
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.ovz69fb_x {
  stop-color: var(--svg-color--483637, #483637);
}

.q7zrt5s0u {
  cx: 26px;
  cy: 28px;
  r: 1px;
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.tgyqa-2it {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 27.75c1.538 0 3-1.25 3-3");
}

.u-atv7afl {
  fill: var(--svg-color--5092ff, #5092FF);
  d: path("M8.414 3L3 8.414V5.586L5.586 3zm5 0L3 13.414v-2.828L10.586 3z");
}

.u-ob932te {
  stroke: var(--svg-color--00a6ed, #00A6ED);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.648 19.83h7.854a3.043 3.043 0 0 0 3.042-2.956l.008-.29a2.76 2.76 0 0 0-2.761-2.84h-.062a2.147 2.147 0 0 0-2.148 2.148v.314c0 .716.58 1.297 1.297 1.297v0c.716 0 1.296-.58 1.296-1.297v-.047");
}

.v2u7938xt {
  d: path("M16 29c8.668 0 13-5.82 13-13S24.668 3 16 3S3 8.82 3 16s4.332 13 13 13");
}

.wuo5gfbdq {
  fill: var(--svg-color--bb1d80, #BB1D80);
  d: path("M5 3h12L3 16V5a2 2 0 0 1 2-2");
}

.wvqg5ii8l {
  stroke: var(--svg-color--a0d9ff, #A0D9FF);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M18.367 19.69h7.854a3.043 3.043 0 0 0 3.041-2.957l.009-.289a2.76 2.76 0 0 0-2.761-2.84h-.062a2.147 2.147 0 0 0-2.148 2.148v.314c0 .716.58 1.296 1.297 1.296v0c.716 0 1.296-.58 1.296-1.296v-.048");
}

.yc0-1ibos {
  cx: 9px;
  cy: 20px;
  r: 1px;
}

.z3x9-tb2n {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M24.75 8.75c1.538 0 3-1.25 3-3");
}

.ztk3tpbxf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-8px, 1.8px);
  d: path("M18.648 13.06c.215-.548.765-1.641 2.33-1.641c1.506 0 2.104 1.093 2.334 1.64");
}

</style>
