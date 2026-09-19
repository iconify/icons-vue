<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iOjOCGe)"><path fill="url(#ij01Hib)" class="f7p6tkbxz"/><path fill="url(#iVXjKnl)" class="f7p6tkbxz"/><path fill="url(#itmwPRb)" class="f7p6tkbxz"/><path fill="url(#iTLaT1b)" class="f7p6tkbxz"/><path fill="url(#iUAcNFV)" class="f7p6tkbxz"/><path fill="url(#iBe1Epe)" class="f7p6tkbxz"/><path fill="url(#iMAWMFb)" class="f7p6tkbxz"/><path fill="url(#iYEc1nd)" class="f7p6tkbxz"/><path fill="url(#igfGIsd)" class="f7p6tkbxz"/></g><path fill="url(#iYVTPec)" class="f7p6tkbxz"/><path fill="url(#iw3gRSb)" class="f7p6tkbxz"/><rect fill="url(#ia7NQlb)" class="yepf0fbcr"/><rect fill="url(#iefuyXd)" class="yepf0fbcr"/><rect fill="url(#iuz7Lgd)" class="yepf0fbcr"/><rect fill="url(#i8nuNqd)" class="yepf0fbcr"/><g filter="url(#iII83Jb)"><path stroke="url(#i4JWrLe)" class="q_7w00bst"/></g><g filter="url(#imfLbeb)"><path stroke="url(#iibEd4H)" class="obf4jpw-q"/></g><g filter="url(#ixJoEje)"><path stroke="url(#i0v3GIe)" class="rsndbbg_u"/></g><g filter="url(#iRyDygb)"><path stroke="url(#ioofzFd)" class="x9k5_onzk"/></g><defs><radialGradient id="ij01Hib" cx="0" cy="0" r="1" gradientTransform="rotate(130.4 8.799 12.719)scale(19.2866 13.5561)" gradientUnits="userSpaceOnUse"><stop class="hy3u76v1i"/><stop offset="1" class="u105b3brp"/></radialGradient><radialGradient id="iVXjKnl" cx="0" cy="0" r="1" gradientTransform="matrix(1.53125 2.84374 -2.45715 1.32308 8.438 13.45)" gradientUnits="userSpaceOnUse"><stop class="wfqjsf-6f"/><stop offset="1" class="zr29k5q_e"/></radialGradient><radialGradient id="itmwPRb" cx="0" cy="0" r="1" gradientTransform="matrix(.2806 2.65005 -2.93551 .31082 7.512 15.198)" gradientUnits="userSpaceOnUse"><stop class="sa36ev_ej"/><stop offset="1" class="y9clnibqj"/></radialGradient><radialGradient id="iTLaT1b" cx="0" cy="0" r="1" gradientTransform="matrix(1.52767 -1.0912 .78395 1.09753 17.831 11.83)" gradientUnits="userSpaceOnUse"><stop class="gja9u5jyb"/><stop offset="1" class="jnyqczbzd"/></radialGradient><radialGradient id="iUAcNFV" cx="0" cy="0" r="1" gradientTransform="rotate(133.299 9.003 10.92)scale(2.23279 1.21415)" gradientUnits="userSpaceOnUse"><stop class="wt9r9wdhk"/><stop offset="1" class="e8o4mybdd"/></radialGradient><radialGradient id="iBe1Epe" cx="0" cy="0" r="1" gradientTransform="rotate(130.957 9.905 12.492)scale(2.93794 3.62296)" gradientUnits="userSpaceOnUse"><stop class="ashh42b-d"/><stop offset="1" class="q4tsknboy"/></radialGradient><radialGradient id="iMAWMFb" cx="0" cy="0" r="1" gradientTransform="matrix(-.95712 2.1193 -1.60697 -.72574 20.544 12.578)" gradientUnits="userSpaceOnUse"><stop class="yrfqoftag"/><stop offset="1" class="npoy1nuha"/></radialGradient><radialGradient id="iYEc1nd" cx="0" cy="0" r="1" gradientTransform="rotate(46.202 -13.867 17.735)scale(1.58029 .60823)" gradientUnits="userSpaceOnUse"><stop class="tfu_1n5kq"/><stop offset="1" class="liwrkbn5w"/></radialGradient><radialGradient id="igfGIsd" cx="0" cy="0" r="1" gradientTransform="matrix(.85937 2.34375 -1.4916 .54692 12.39 11.781)" gradientUnits="userSpaceOnUse"><stop class="nq7m07y8l"/><stop offset="1" class="iqcb6-dgh"/></radialGradient><radialGradient id="iYVTPec" cx="0" cy="0" r="1" gradientTransform="matrix(-18.56652 4.0743 -6.61005 -30.12186 25.541 19.076)" gradientUnits="userSpaceOnUse"><stop offset=".866" class="w9p5x8fww"/><stop offset="1" class="fjb3328lw"/></radialGradient><radialGradient id="iw3gRSb" cx="0" cy="0" r="1" gradientTransform="matrix(-18.34738 4.08297 -6.6241 -29.76625 25.541 19.076)" gradientUnits="userSpaceOnUse"><stop offset=".976" class="y652_po6l"/><stop offset="1" class="e7lrplx5j"/></radialGradient><linearGradient id="ia7NQlb" x1="13.092" x2="15.793" y1="9.78" y2="9.78" gradientUnits="userSpaceOnUse"><stop class="a0o7j62ob"/><stop offset="1" class="muf40ih_h"/></linearGradient><linearGradient id="iefuyXd" x1="18.889" x2="15.27" y1="10.783" y2="11.35" gradientUnits="userSpaceOnUse"><stop class="xo_axzbon"/><stop offset="1" class="zjkcifb5v"/></linearGradient><linearGradient id="iuz7Lgd" x1="14.733" x2="13.759" y1="14.287" y2="15.621" gradientUnits="userSpaceOnUse"><stop class="o178q4qly"/><stop offset="1" class="yle0k1bln"/></linearGradient><linearGradient id="i8nuNqd" x1="15.314" x2="17.057" y1="14.595" y2="15.86" gradientUnits="userSpaceOnUse"><stop class="zc-v1zkae"/><stop offset="1" class="s_7vwde6n"/></linearGradient><linearGradient id="i4JWrLe" x1="24.565" x2="20.575" y1="14.264" y2="30.054" gradientUnits="userSpaceOnUse"><stop class="n1eyhb-al"/><stop offset="1" class="v-7wawbns"/></linearGradient><linearGradient id="iibEd4H" x1="17.212" x2="9.854" y1="3.293" y2="15.396" gradientUnits="userSpaceOnUse"><stop class="va9v0b5_h"/><stop offset="1" class="xatc7mh8t"/></linearGradient><linearGradient id="i0v3GIe" x1="17.974" x2="17.68" y1="13.246" y2="17.455" gradientUnits="userSpaceOnUse"><stop class="fxywcj73h"/><stop offset="1" class="xrdcusbnk"/></linearGradient><linearGradient id="ioofzFd" x1="11.656" x2="11.966" y1="12.875" y2="16.619" gradientUnits="userSpaceOnUse"><stop class="yc13-mbqm"/><stop offset="1" class="yxsvup0eg"/></linearGradient><filter id="iOjOCGe" width="19.914" height="28.977" x="6.168" y="1.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.254902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5364"/></filter><filter id="iII83Jb" width="8.938" height="16.887" x="18.359" y="11.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5364" stdDeviation="1.25"/></filter><filter id="imfLbeb" width="3.75" height="13.8" x="14.125" y="2.283" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5364" stdDeviation=".625"/></filter><filter id="ixJoEje" width="4.222" height="4.735" x="14.28" y="12.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5364" stdDeviation=".375"/></filter><filter id="iRyDygb" width="4.722" height="5.235" x="11.398" y="12.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5364" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:middle-finger-medium-dark" /></template>
<style>
.a0o7j62ob {
  stop-color: var(--svg-color--79534d, #79534D);
}

.ashh42b-d {
  stop-color: var(--svg-color--a07a6a, #A07A6A);
}

.e7lrplx5j {
  stop-color: var(--svg-color--835c59, #835C59);
}

.e8o4mybdd {
  stop-color: var(--svg-color--896f67, #896F67);
  stop-opacity: 0;
}

.f7p6tkbxz {
  d: path("M12.645 4.402a2.39 2.39 0 0 1 4.78 0v7.587a2.391 2.391 0 0 1 4.242 1.146a2.39 2.39 0 0 1 4.119 2.07l-.29 2.854c-.117 1.242-.84 6.046-2.527 7.937c-1.825 2.456-4.576 3.992-7.645 3.992A8.353 8.353 0 0 1 7.03 22.62l-.784-4.457a2.28 2.28 0 0 1 2.6-2.835a2.602 2.602 0 0 1 3.798-3.11z");
}

.fjb3328lw {
  stop-color: var(--svg-color--764f49, #764F49);
}

.ft5dv1b6b {
  fill: none;
}

.fxywcj73h {
  stop-color: var(--svg-color--a47f73, #A47F73);
}

.gja9u5jyb {
  stop-color: var(--svg-color--74584e, #74584E);
}

.hy3u76v1i {
  stop-color: var(--svg-color--926760, #926760);
}

.iqcb6-dgh {
  stop-color: var(--svg-color--5d4038, #5D4038);
  stop-opacity: 0;
}

.jnyqczbzd {
  stop-color: var(--svg-color--74584e, #74584E);
  stop-opacity: 0;
}

.liwrkbn5w {
  stop-color: var(--svg-color--654940, #654940);
  stop-opacity: 0;
}

.muf40ih_h {
  stop-color: var(--svg-color--79534d, #79534D);
  stop-opacity: 0;
}

.n1eyhb-al {
  stop-color: var(--svg-color--a68074, #A68074);
}

.npoy1nuha {
  stop-color: var(--svg-color--a07c6d, #A07C6D);
  stop-opacity: 0;
}

.nq7m07y8l {
  stop-color: var(--svg-color--5d4038, #5D4038);
}

.o178q4qly {
  stop-color: var(--svg-color--8c5f5e, #8C5F5E);
  stop-opacity: 0;
}

.obf4jpw-q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M16 4.158v10.05");
}

.q_7w00bst {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M24.048 14.937c-.046 1.014-.215 3.148-.695 5.676s-1.362 4.194-1.744 4.711");
}

.q4tsknboy {
  stop-color: var(--svg-color--a07a6a, #A07A6A);
  stop-opacity: 0;
}

.rsndbbg_u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m15.28 16.03l2.222-2.734");
}

.s_7vwde6n {
  stop-color: var(--svg-color--8f625f, #8F625F);
}

.sa36ev_ej {
  stop-color: var(--svg-color--72584e, #72584E);
}

.tfu_1n5kq {
  stop-color: var(--svg-color--654940, #654940);
}

.u105b3brp {
  stop-color: var(--svg-color--895b5d, #895B5D);
}

.v-7wawbns {
  stop-color: var(--svg-color--a68074, #A68074);
  stop-opacity: 0;
}

.va9v0b5_h {
  stop-color: var(--svg-color--a27f72, #A27F72);
}

.w9p5x8fww {
  stop-color: var(--svg-color--764f49, #764F49);
  stop-opacity: 0;
}

.wfqjsf-6f {
  stop-color: var(--svg-color--765448, #765448);
}

.wt9r9wdhk {
  stop-color: var(--svg-color--896f67, #896F67);
}

.x9k5_onzk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m14.87 16.03l-2.222-2.734");
}

.xatc7mh8t {
  stop-color: var(--svg-color--a27f72, #A27F72);
  stop-opacity: 0;
}

.xo_axzbon {
  stop-color: var(--svg-color--9c7264, #9C7264);
}

.xrdcusbnk {
  stop-color: var(--svg-color--a47f73, #A47F73);
  stop-opacity: 0;
}

.y652_po6l {
  stop-color: var(--svg-color--835c59, #835C59);
  stop-opacity: 0;
}

.y9clnibqj {
  stop-color: var(--svg-color--72584e, #72584E);
  stop-opacity: 0;
}

.yc13-mbqm {
  stop-color: var(--svg-color--623b30, #623B30);
}

.yepf0fbcr {
  width: 4.781px;
  height: 14.813px;
  x: 12.648px;
  y: 2.012px;
  rx: 2.391px;
}

.yle0k1bln {
  stop-color: var(--svg-color--8c5f5e, #8C5F5E);
}

.yrfqoftag {
  stop-color: var(--svg-color--a07c6d, #A07C6D);
}

.yxsvup0eg {
  stop-color: var(--svg-color--623b30, #623B30);
  stop-opacity: 0;
}

.zc-v1zkae {
  stop-color: var(--svg-color--8f625f, #8F625F);
  stop-opacity: 0;
}

.zjkcifb5v {
  stop-color: var(--svg-color--9c7264, #9C7264);
  stop-opacity: 0;
}

.zr29k5q_e {
  stop-color: var(--svg-color--765448, #765448);
  stop-opacity: 0;
}

</style>
