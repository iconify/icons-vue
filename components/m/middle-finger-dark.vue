<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iqXI3Kd)"><path fill="url(#iH1AVGe)" class="f7p6tkbxz"/><path fill="url(#iAttfhc)" class="f7p6tkbxz"/><path fill="url(#iUgcCJc)" class="f7p6tkbxz"/><path fill="url(#iLkkXAc)" class="f7p6tkbxz"/><path fill="url(#i7F45Ud)" class="f7p6tkbxz"/><path fill="url(#iqeNEMq)" class="f7p6tkbxz"/><path fill="url(#iIpsNzb)" class="f7p6tkbxz"/><path fill="url(#iC38Tgd)" class="f7p6tkbxz"/><path fill="url(#iyMi4oc)" class="f7p6tkbxz"/></g><rect fill="url(#i2K7Vrd)" class="yepf0fbcr"/><rect fill="url(#i6LeLFe)" class="yepf0fbcr"/><rect fill="url(#iX64fNO)" class="yepf0fbcr"/><rect fill="url(#i8SqeYb)" class="yepf0fbcr"/><g filter="url(#iUqdbwe)"><path stroke="url(#iEMVrvd)" class="q_7w00bst"/></g><g filter="url(#ip9Dqqd)"><path stroke="url(#idiUOgd)" class="obf4jpw-q"/></g><g filter="url(#il2Ldyb)"><path stroke="url(#ivDovsd)" class="rsndbbg_u"/></g><g filter="url(#iW5V4lb)"><path stroke="url(#iQsJN3b)" class="x9k5_onzk"/></g><defs><radialGradient id="iH1AVGe" cx="0" cy="0" r="1" gradientTransform="rotate(130.4 8.799 12.719)scale(19.2866 13.5561)" gradientUnits="userSpaceOnUse"><stop class="va6741bfo"/><stop offset="1" class="r8us_1bpp"/></radialGradient><radialGradient id="iAttfhc" cx="0" cy="0" r="1" gradientTransform="matrix(1.53125 2.84374 -2.45715 1.32308 8.438 13.45)" gradientUnits="userSpaceOnUse"><stop class="ehlxef60a"/><stop offset="1" class="qt_qnsbca"/></radialGradient><radialGradient id="iUgcCJc" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.63672 -1.41421 .86405 6.719 16)" gradientUnits="userSpaceOnUse"><stop class="im_cozbld"/><stop offset="1" class="ot6oaqh5v"/></radialGradient><radialGradient id="iLkkXAc" cx="0" cy="0" r="1" gradientTransform="rotate(109.231 5.561 11.763)scale(2.84632 1.10477)" gradientUnits="userSpaceOnUse"><stop class="cv72mt8pq"/><stop offset="1" class="hx5bluqto"/></radialGradient><radialGradient id="i7F45Ud" cx="0" cy="0" r="1" gradientTransform="rotate(133.299 9.003 10.92)scale(2.23279 1.21415)" gradientUnits="userSpaceOnUse"><stop class="hawca0dcs"/><stop offset="1" class="zezxwccfo"/></radialGradient><radialGradient id="iqeNEMq" cx="0" cy="0" r="1" gradientTransform="rotate(130.957 9.905 12.492)scale(2.93794 3.62296)" gradientUnits="userSpaceOnUse"><stop class="r9-ihob4z"/><stop offset="1" class="zzhv4sb-f"/></radialGradient><radialGradient id="iIpsNzb" cx="0" cy="0" r="1" gradientTransform="matrix(-.95712 2.1193 -1.60697 -.72574 20.544 12.578)" gradientUnits="userSpaceOnUse"><stop class="ztpvcgb-y"/><stop offset="1" class="uh0yn9b_x"/></radialGradient><radialGradient id="iC38Tgd" cx="0" cy="0" r="1" gradientTransform="rotate(46.202 -13.867 17.735)scale(1.58029 .60823)" gradientUnits="userSpaceOnUse"><stop class="m3gkz_b7w"/><stop offset="1" class="h5xkksrlc"/></radialGradient><radialGradient id="iyMi4oc" cx="0" cy="0" r="1" gradientTransform="matrix(.85937 2.34375 -1.4916 .54692 12.39 11.781)" gradientUnits="userSpaceOnUse"><stop class="m3gkz_b7w"/><stop offset="1" class="h5xkksrlc"/></radialGradient><linearGradient id="i2K7Vrd" x1="13.092" x2="15.793" y1="9.78" y2="9.78" gradientUnits="userSpaceOnUse"><stop class="oo1yeetnn"/><stop offset="1" class="g8iz7-arv"/></linearGradient><linearGradient id="i6LeLFe" x1="18.889" x2="15.27" y1="10.783" y2="11.35" gradientUnits="userSpaceOnUse"><stop class="ke67f3dpk"/><stop offset="1" class="tr66d8__w"/></linearGradient><linearGradient id="iX64fNO" x1="14.733" x2="13.759" y1="14.287" y2="15.621" gradientUnits="userSpaceOnUse"><stop class="q5vf_pbsm"/><stop offset="1" class="r74hbskxc"/></linearGradient><linearGradient id="i8SqeYb" x1="15.314" x2="17.057" y1="14.595" y2="15.86" gradientUnits="userSpaceOnUse"><stop class="q5vf_pbsm"/><stop offset="1" class="r74hbskxc"/></linearGradient><linearGradient id="iEMVrvd" x1="24.565" x2="20.575" y1="14.264" y2="30.054" gradientUnits="userSpaceOnUse"><stop class="i2gh4s8vi"/><stop offset="1" class="q94j27smd"/></linearGradient><linearGradient id="idiUOgd" x1="17.212" x2="9.854" y1="3.293" y2="15.396" gradientUnits="userSpaceOnUse"><stop class="ok65aabmb"/><stop offset="1" class="j30gkmbty"/></linearGradient><linearGradient id="ivDovsd" x1="17.974" x2="17.68" y1="13.246" y2="17.455" gradientUnits="userSpaceOnUse"><stop class="z_ok4qbes"/><stop offset="1" class="m2rehs_5n"/></linearGradient><linearGradient id="iQsJN3b" x1="11.656" x2="11.966" y1="12.875" y2="16.619" gradientUnits="userSpaceOnUse"><stop class="lu3w2fb0v"/><stop offset="1" class="l-rvk4teq"/></linearGradient><filter id="iqXI3Kd" width="19.914" height="28.977" x="6.168" y="1.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.129412 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5357"/></filter><filter id="iUqdbwe" width="8.938" height="16.887" x="18.359" y="11.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5357" stdDeviation="1.25"/></filter><filter id="ip9Dqqd" width="3.75" height="13.8" x="14.125" y="2.283" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5357" stdDeviation=".625"/></filter><filter id="il2Ldyb" width="4.222" height="4.735" x="14.28" y="12.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5357" stdDeviation=".375"/></filter><filter id="iW5V4lb" width="4.722" height="5.235" x="11.398" y="12.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5357" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:middle-finger-dark" /></template>
<style>
.cv72mt8pq {
  stop-color: var(--svg-color--3e3231, #3E3231);
}

.ehlxef60a {
  stop-color: var(--svg-color--483632, #483632);
}

.f7p6tkbxz {
  d: path("M12.645 4.402a2.39 2.39 0 0 1 4.78 0v7.587a2.391 2.391 0 0 1 4.242 1.146a2.39 2.39 0 0 1 4.119 2.07l-.29 2.854c-.117 1.242-.84 6.046-2.527 7.937c-1.825 2.456-4.576 3.992-7.645 3.992A8.353 8.353 0 0 1 7.03 22.62l-.784-4.457a2.28 2.28 0 0 1 2.6-2.835a2.602 2.602 0 0 1 3.798-3.11z");
}

.ft5dv1b6b {
  fill: none;
}

.g8iz7-arv {
  stop-color: var(--svg-color--443130, #443130);
  stop-opacity: 0;
}

.h5xkksrlc {
  stop-color: var(--svg-color--362523, #362523);
  stop-opacity: 0;
}

.hawca0dcs {
  stop-color: var(--svg-color--423130, #423130);
}

.hx5bluqto {
  stop-color: var(--svg-color--3e3231, #3E3231);
  stop-opacity: 0;
}

.i2gh4s8vi {
  stop-color: var(--svg-color--755d5b, #755D5B);
}

.im_cozbld {
  stop-color: var(--svg-color--443230, #443230);
}

.j30gkmbty {
  stop-color: var(--svg-color--66514f, #66514F);
  stop-opacity: 0;
}

.ke67f3dpk {
  stop-color: var(--svg-color--5b433f, #5B433F);
}

.l-rvk4teq {
  stop-color: var(--svg-color--281614, #281614);
  stop-opacity: 0;
}

.lu3w2fb0v {
  stop-color: var(--svg-color--281614, #281614);
}

.m2rehs_5n {
  stop-color: var(--svg-color--66524f, #66524F);
  stop-opacity: 0;
}

.m3gkz_b7w {
  stop-color: var(--svg-color--362523, #362523);
}

.obf4jpw-q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M16 4.158v10.05");
}

.ok65aabmb {
  stop-color: var(--svg-color--66514f, #66514F);
}

.oo1yeetnn {
  stop-color: var(--svg-color--443130, #443130);
}

.ot6oaqh5v {
  stop-color: var(--svg-color--443230, #443230);
  stop-opacity: 0;
}

.q_7w00bst {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M24.048 14.937c-.046 1.014-.215 3.148-.695 5.676s-1.362 4.194-1.744 4.711");
}

.q5vf_pbsm {
  stop-color: var(--svg-color--4e3538, #4E3538);
  stop-opacity: 0;
}

.q94j27smd {
  stop-color: var(--svg-color--755d5b, #755D5B);
  stop-opacity: 0;
}

.qt_qnsbca {
  stop-color: var(--svg-color--483632, #483632);
  stop-opacity: 0;
}

.r74hbskxc {
  stop-color: var(--svg-color--4e3538, #4E3538);
}

.r8us_1bpp {
  stop-color: var(--svg-color--4b3135, #4B3135);
}

.r9-ihob4z {
  stop-color: var(--svg-color--614a46, #614A46);
}

.rsndbbg_u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m15.28 16.03l2.222-2.734");
}

.tr66d8__w {
  stop-color: var(--svg-color--5b433f, #5B433F);
  stop-opacity: 0;
}

.uh0yn9b_x {
  stop-color: var(--svg-color--634c49, #634C49);
  stop-opacity: 0;
}

.va6741bfo {
  stop-color: var(--svg-color--533c3b, #533C3B);
}

.x9k5_onzk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m14.87 16.03l-2.222-2.734");
}

.yepf0fbcr {
  width: 4.781px;
  height: 14.813px;
  x: 12.648px;
  y: 2.012px;
  rx: 2.391px;
}

.z_ok4qbes {
  stop-color: var(--svg-color--66524f, #66524F);
}

.zezxwccfo {
  stop-color: var(--svg-color--423130, #423130);
  stop-opacity: 0;
}

.ztpvcgb-y {
  stop-color: var(--svg-color--624b48, #624B48);
}

.zzhv4sb-f {
  stop-color: var(--svg-color--614a46, #614A46);
  stop-opacity: 0;
}

</style>
