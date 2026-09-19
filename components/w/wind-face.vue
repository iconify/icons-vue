<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iC2lLce)" class="fx1xgib3p"/><path fill="url(#i5xOJZc)" class="fx1xgib3p"/><path fill="url(#i9Kr4ek)" class="fx1xgib3p"/><path fill="url(#imL89Rz)" class="fx1xgib3p"/><path fill="url(#ilmjMwe)" class="fx1xgib3p"/><path fill="url(#iwNlvVc)" class="fx1xgib3p"/><path fill="url(#iCaP1Qc)" class="fx1xgib3p"/><path fill="url(#iSkC91d)" class="fx1xgib3p"/><path fill="url(#i1ZESUd)" class="fx1xgib3p"/><path fill="url(#ihcno9h)" class="fx1xgib3p"/><path fill="url(#itskHYb)" class="fx1xgib3p"/><g filter="url(#iUbpNEd)"><path clip-rule="evenodd" class="oz288vo2g"/></g><g filter="url(#ilMa5Tc)"><path clip-rule="evenodd" class="dpzk3ccjv"/></g><g filter="url(#ieWtg0d)"><path class="y3jye8wyn"/></g><g filter="url(#iFYxwHe)"><path class="th052uhjh"/><path fill="url(#izqNIGe)" class="lbw5udu_g"/></g><path fill="url(#isY66mc)" class="lbw5udu_g"/><path fill="url(#ispp1Cd)" class="lbw5udu_g"/><path fill="url(#inWULsD)" class="zqn1_9bbj"/><path fill="url(#iNGhHCe)" class="zqn1_9bbj"/><path fill="url(#ioQyTsO)" class="zqn1_9bbj"/><path fill="url(#ihfc2xd)" class="zqn1_9bbj"/><path fill="url(#iZqiYpb)" class="zqn1_9bbj"/><path fill="url(#iCFg3te)" class="zqn1_9bbj"/><g filter="url(#iXKxm4H)"><path class="trfkg6bth"/><path fill="url(#icsrFJe)" class="kinobwb9a"/><path fill="url(#iXZzbyx)" class="kinobwb9a"/><path fill="url(#iDA3FNc)" class="kinobwb9a"/><path fill="url(#inbz1tc)" class="kinobwb9a"/><path fill="url(#iuZOddd)" class="kinobwb9a"/><path fill="url(#iV5P8id)" class="kinobwb9a"/><path fill="url(#i6k2kce)" class="kinobwb9a"/></g><path fill="url(#ikELgMe)" class="kinobwb9a"/><path fill="url(#ioGRNRc)" class="kinobwb9a"/><g filter="url(#iNgAy8b)"><circle fill="url(#i0HfTUc)" class="l_lf4obzm"/></g><g filter="url(#iWXPW0d)"><circle fill="url(#i20j4Et)" class="d3oo0xbat"/><circle fill="url(#idDQKve)" class="d3oo0xbat"/></g><g filter="url(#ioTfSwc)"><path fill="url(#io9t9Hd)" class="vdysjzt7h"/></g><defs><radialGradient id="i5xOJZc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6 -4.14834 0 16.635 10.98)" gradientUnits="userSpaceOnUse"><stop class="olyy75brn"/><stop offset="1" class="c954lwbwo"/></radialGradient><radialGradient id="i9Kr4ek" cx="0" cy="0" r="1" gradientTransform="matrix(-2.43748 -3.71876 1.86096 -1.21977 19.355 19.04)" gradientUnits="userSpaceOnUse"><stop class="olyy75brn"/><stop offset="1" class="c954lwbwo"/></radialGradient><radialGradient id="imL89Rz" cx="0" cy="0" r="1" gradientTransform="rotate(-134.012 13.832 6.987)scale(2.56364 1.36829)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="yqrkw9bjm"/><stop offset="1" class="knhpxhbxj"/></radialGradient><radialGradient id="ilmjMwe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22445 1.74149 -.54557 -1.6367 11.738 9.088)" gradientUnits="userSpaceOnUse"><stop class="aj85ieeev"/><stop offset="1" class="fu1o43bpx"/></radialGradient><radialGradient id="iwNlvVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.029 3.08431 0 14.692 27.962)" gradientUnits="userSpaceOnUse"><stop class="en296acwp"/><stop offset="1" class="wfchz7fwt"/></radialGradient><radialGradient id="iSkC91d" cx="0" cy="0" r="1" gradientTransform="rotate(-176.729 9.395 11.735)scale(2.03505 .7382)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="ksctbybyx"/><stop offset="1" class="y_7gj1bsi"/></radialGradient><radialGradient id="i1ZESUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53107 -1.11476 .48341 -.66395 17.333 26.32)" gradientUnits="userSpaceOnUse"><stop class="hv0n7sb4a"/><stop offset="1" class="y_7gj1bsi"/></radialGradient><radialGradient id="ihcno9h" cx="0" cy="0" r="1" gradientTransform="rotate(-100.491 17.819 4.339)scale(.67216 1.50966)" gradientUnits="userSpaceOnUse"><stop class="xh5--389s"/><stop offset="1" class="qj4xl8b8v"/></radialGradient><radialGradient id="itskHYb" cx="0" cy="0" r="1" gradientTransform="matrix(.2203 -.53853 1.20953 .4948 16.7 24.534)" gradientUnits="userSpaceOnUse"><stop class="xh5--389s"/><stop offset="1" class="qj4xl8b8v"/></radialGradient><radialGradient id="izqNIGe" cx="0" cy="0" r="1" gradientTransform="matrix(-.26563 -1.34375 2.84697 -.56279 13.465 14.321)" gradientUnits="userSpaceOnUse"><stop class="n9iqe8bip"/><stop offset="1" class="cvieop8yk"/></radialGradient><radialGradient id="isY66mc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.8203 .42391 -.17988 -1.19677 14.73 12.657)" gradientUnits="userSpaceOnUse"><stop class="cvlu93_dx"/><stop offset="1" class="q54h_abid"/></radialGradient><radialGradient id="ispp1Cd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.06273 -.04688 .04271 -.96813 15.215 12.76)" gradientUnits="userSpaceOnUse"><stop class="cvlu93_dx"/><stop offset="1" class="wwl9kxb6t"/></radialGradient><radialGradient id="ioQyTsO" cx="0" cy="0" r="1" gradientTransform="rotate(162.181 6.247 6.012)scale(5.43623 2.8168)" gradientUnits="userSpaceOnUse"><stop class="x9wlabc9g"/><stop offset="1" class="y86ixgbio"/></radialGradient><radialGradient id="ihfc2xd" cx="0" cy="0" r="1" gradientTransform="rotate(122.005 7.483 5.804)scale(6.70514 5.0025)" gradientUnits="userSpaceOnUse"><stop class="wvblunb8o"/><stop offset="1" class="itwfpccfo"/></radialGradient><radialGradient id="iZqiYpb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.4741 5.52372 0 9.167 20.42)" gradientUnits="userSpaceOnUse"><stop class="u8f82jbbs"/><stop offset="1" class="y56y4oyzb"/></radialGradient><radialGradient id="icsrFJe" cx="0" cy="0" r="1" gradientTransform="rotate(52.125 -12.592 35.39)scale(3.56305 7.13158)" gradientUnits="userSpaceOnUse"><stop class="o8ezx_kjy"/><stop offset="1" class="v__1ogpqq"/></radialGradient><radialGradient id="iXZzbyx" cx="0" cy="0" r="1" gradientTransform="rotate(169.355 14.144 12.509)scale(5.27834 9.04973)" gradientUnits="userSpaceOnUse"><stop class="hfkcwccxp"/><stop offset="1" class="x8dvo4byn"/></radialGradient><radialGradient id="iDA3FNc" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 -3.40625 3.40193 -.12484 27.355 26.102)" gradientUnits="userSpaceOnUse"><stop class="fgiy_tsgz"/><stop offset="1" class="wszlyidlp"/></radialGradient><radialGradient id="inbz1tc" cx="0" cy="0" r="1" gradientTransform="matrix(.26486 -2.95313 3.27086 .29336 24.372 27.618)" gradientUnits="userSpaceOnUse"><stop class="bo7hlub5b"/><stop offset="1" class="c3a36xb6s"/></radialGradient><radialGradient id="iuZOddd" cx="0" cy="0" r="1" gradientTransform="rotate(-10.899 139.71 -91.85)scale(5.12367 2.47035)" gradientUnits="userSpaceOnUse"><stop class="lt_i0k0ik"/><stop offset="1" class="r_mr1sqsb"/></radialGradient><radialGradient id="iV5P8id" cx="0" cy="0" r="1" gradientTransform="matrix(1.79891 -1.51988 1.00224 1.18624 22.573 26.586)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="ro5r6cc4i"/><stop offset="1" class="x6oe0pbyu"/></radialGradient><radialGradient id="i6k2kce" cx="0" cy="0" r="1" gradientTransform="rotate(149.808 10.247 12.742)scale(3.97698 4.89928)" gradientUnits="userSpaceOnUse"><stop class="v5id5xm0y"/><stop offset="1" class="eyowkw55r"/></radialGradient><radialGradient id="ikELgMe" cx="0" cy="0" r="1" gradientTransform="rotate(114.608 8.168 17.604)scale(4.50271 4.70885)" gradientUnits="userSpaceOnUse"><stop class="fl7d28bnz"/><stop offset="1" class="cllu7nn7q"/></radialGradient><radialGradient id="ioGRNRc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.42104 1.71871 -1.7974 -4.62343 30.12 19.884)" gradientUnits="userSpaceOnUse"><stop class="fl7d28bnz"/><stop offset="1" class="cllu7nn7q"/></radialGradient><radialGradient id="i0HfTUc" cx="0" cy="0" r="1" gradientTransform="rotate(104.036 5.317 18.357)scale(5.01373)" gradientUnits="userSpaceOnUse"><stop offset=".529" class="i2m6i-bnf"/><stop offset="1" class="uingq-bue"/></radialGradient><radialGradient id="i20j4Et" cx="0" cy="0" r="1" gradientTransform="rotate(145.856 11.792 14.962)scale(6.56994)" gradientUnits="userSpaceOnUse"><stop offset=".292" class="senet9b-v"/><stop offset="1" class="p3oua-6_w"/></radialGradient><radialGradient id="idDQKve" cx="0" cy="0" r="1" gradientTransform="rotate(97.96 5.579 21.303)scale(7.44675)" gradientUnits="userSpaceOnUse"><stop offset=".724" class="wszlyidlp"/><stop offset="1" class="fgiy_tsgz"/></radialGradient><radialGradient id="io9t9Hd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.62502 2.08592 -1.74433 -1.3589 25.012 25.084)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="g9p_vdptf"/><stop offset="1" class="oz02owv1k"/></radialGradient><filter id="iUbpNEd" width="4.48" height="2.103" x="11.583" y="16.12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15324" stdDeviation=".1"/></filter><filter id="ilMa5Tc" width="4.58" height="1.853" x="11.98" y="16.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0745098 0 0 0 0 0.168627 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15324"/></filter><filter id="ieWtg0d" width="4.489" height="2.258" x="10.682" y="12.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15324" stdDeviation=".1"/></filter><filter id="iFYxwHe" width="4.514" height="1.958" x="10.951" y="12.152" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0901961 0 0 0 0 0.32549 0 0 0 0 0.670588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15324"/></filter><filter id="iXKxm4H" width="11.497" height="10.48" x="18.623" y="16.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.478431 0 0 0 0 0.690196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15324"/></filter><filter id="iNgAy8b" width="6.144" height="6.144" x="20.861" y="16.771" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15324" stdDeviation=".2"/></filter><filter id="iWXPW0d" width="8.063" height="8.063" x="22.387" y="18.227" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15324" stdDeviation=".25"/></filter><filter id="ioTfSwc" width="3.48" height="3.404" x="22.385" y="24.166" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15324" stdDeviation=".2"/></filter><linearGradient id="iC2lLce" x1="17.017" x2="17.017" y1="9.919" y2="31.727" gradientUnits="userSpaceOnUse"><stop class="r3498vbtj"/><stop offset="1" class="khcn4ja7v"/></linearGradient><linearGradient id="iCaP1Qc" x1="10.515" x2="10.515" y1="30.415" y2="27.602" gradientUnits="userSpaceOnUse"><stop class="qyxrx7qcu"/><stop offset="1" class="lk-rcfb6x"/></linearGradient><linearGradient id="inWULsD" x1=".557" x2="15.572" y1="16" y2="16" gradientUnits="userSpaceOnUse"><stop class="illicwb4s"/><stop offset="1" class="vnoz_qbee"/></linearGradient><linearGradient id="iNGhHCe" x1="13.706" x2="8.731" y1=".491" y2="21.636" gradientUnits="userSpaceOnUse"><stop class="bvfd-fq0i"/><stop offset="1" class="el6fzccem"/></linearGradient><linearGradient id="iCFg3te" x1="4.887" x2="4.887" y1="31.29" y2="25.79" gradientUnits="userSpaceOnUse"><stop class="aq11bmbaa"/><stop offset="1" class="m8n8j5c8g"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:wind-face" /></template>
<style>
.aj85ieeev {
  stop-color: var(--svg-color--1f84cf, #1F84CF);
}

.aq11bmbaa {
  stop-color: var(--svg-color--384b91, #384B91);
}

.bo7hlub5b {
  stop-color: var(--svg-color--3678b3, #3678B3);
}

.bvfd-fq0i {
  stop-color: var(--svg-color--4996d2, #4996D2);
}

.c3a36xb6s {
  stop-color: var(--svg-color--3678b3, #3678B3);
  stop-opacity: 0;
}

.c954lwbwo {
  stop-color: var(--svg-color--5debff, #5DEBFF);
  stop-opacity: 0;
}

.cllu7nn7q {
  stop-color: var(--svg-color--66f0ff, #66F0FF);
  stop-opacity: 0;
}

.cvieop8yk {
  stop-color: var(--svg-color--1255b1, #1255B1);
  stop-opacity: 0;
}

.cvlu93_dx {
  stop-color: var(--svg-color--52c4ff, #52C4FF);
}

.d3oo0xbat {
  cx: 26.418px;
  cy: 22.259px;
  r: 3.531px;
}

.dpzk3ccjv {
  fill: var(--svg-color--4d4c4e, #4D4C4E);
  fill-rule: evenodd;
  d: path("M15.899 16.302a.5.5 0 0 1 .029.707a2.67 2.67 0 0 1-3.789.147a.5.5 0 1 1 .682-.732c.677.631 1.74.593 2.371-.093a.5.5 0 0 1 .707-.029");
}

.el6fzccem {
  stop-color: var(--svg-color--4996d2, #4996D2);
  stop-opacity: 0;
}

.en296acwp {
  stop-color: var(--svg-color--46d8ff, #46D8FF);
}

.eyowkw55r {
  stop-color: var(--svg-color--5ff5ff, #5FF5FF);
  stop-opacity: 0;
}

.fgiy_tsgz {
  stop-color: var(--svg-color--2e80bf, #2E80BF);
}

.fl7d28bnz {
  stop-color: var(--svg-color--66f0ff, #66F0FF);
}

.ft5dv1b6b {
  fill: none;
}

.fu1o43bpx {
  stop-color: var(--svg-color--1f84cf, #1F84CF);
  stop-opacity: 0;
}

.fx1xgib3p {
  d: path("m2.01 6.28l7.65-.14c4.05 0 7.37 3.32 7.38 7.39v2.761c0 .163.04.324.117.467c.565 1.04.997 1.63 1.302 2.047c.378.516.56.766.56 1.275c0 .95-1.04 1.72-1.99 1.72l-.005.005q-.006.353-.02.695h.026a.98.98 0 0 1 .305 1.912a.98.98 0 1 1-.825 1.765c-.69 2.326-2.275 3.783-5.92 3.783c-.7 0-1.876.008-3.21.016c-1.752.011-3.777.024-5.36.024z");
}

.g9p_vdptf {
  stop-color: var(--svg-color--56e6ff, #56E6FF);
}

.hfkcwccxp {
  stop-color: var(--svg-color--5de8ff, #5DE8FF);
}

.hv0n7sb4a {
  stop-color: var(--svg-color--3a72b9, #3A72B9);
}

.i2m6i-bnf {
  stop-color: var(--svg-color--3591bf, #3591BF);
  stop-opacity: 0;
}

.illicwb4s {
  stop-color: var(--svg-color--284fa2, #284FA2);
}

.itwfpccfo {
  stop-color: var(--svg-color--52c1ff, #52C1FF);
  stop-opacity: 0;
}

.khcn4ja7v {
  stop-color: var(--svg-color--48c5fa, #48C5FA);
}

.kinobwb9a {
  d: path("M26.48 18.54c-.04 0-.17.01-.21.01A2.76 2.76 0 0 0 23.8 17a2.78 2.78 0 0 0-2.78 2.78c0 .546.161 1.052.437 1.48c.279.432.395 1.004.06 1.392c-.643.742-1.528 1.41-2.717 1.638c-.2.04-.24.3-.07.41c.7.44 2.12 1.17 3.93 1.32a1.445 1.445 0 0 0 2.878.097a.17.17 0 0 1 .195-.15a3.6 3.6 0 0 0 .647.063a3.74 3.74 0 0 0 3.74-3.74c0-2.06-1.57-3.75-3.64-3.75");
}

.knhpxhbxj {
  stop-color: var(--svg-color--2598e2, #2598E2);
  stop-opacity: 0;
}

.ksctbybyx {
  stop-color: var(--svg-color--29aced, #29ACED);
}

.l_lf4obzm {
  cx: 23.933px;
  cy: 19.843px;
  r: 2.672px;
}

.lbw5udu_g {
  d: path("M11.48 14.01c-.16 0-.32-.07-.42-.21a.527.527 0 0 1 .1-.74c.06-.05 1.48-1.12 3.59-.87c.29.03.5.3.46.59c-.03.29-.3.5-.59.46c-1.65-.2-2.81.65-2.82.66c-.1.07-.21.11-.32.11");
}

.lk-rcfb6x {
  stop-color: var(--svg-color--3a83b9, #3A83B9);
  stop-opacity: 0;
}

.lt_i0k0ik {
  stop-color: var(--svg-color--4acfec, #4ACFEC);
}

.m8n8j5c8g {
  stop-color: var(--svg-color--384b91, #384B91);
  stop-opacity: 0;
}

.n9iqe8bip {
  stop-color: var(--svg-color--1255b1, #1255B1);
}

.o8ezx_kjy {
  stop-color: var(--svg-color--34a2c9, #34A2C9);
}

.olyy75brn {
  stop-color: var(--svg-color--5debff, #5DEBFF);
}

.oz02owv1k {
  stop-color: var(--svg-color--358cc4, #358CC4);
}

.oz288vo2g {
  fill: var(--svg-color--286aa1, #286AA1);
  fill-rule: evenodd;
  d: path("M15.702 16.452a.5.5 0 0 1 .028.707a2.67 2.67 0 0 1-3.788.147a.5.5 0 0 1 .682-.732a1.67 1.67 0 0 0 2.371-.093a.5.5 0 0 1 .707-.029");
}

.p3oua-6_w {
  stop-color: var(--svg-color--3099cf, #3099CF);
}

.q54h_abid {
  stop-color: var(--svg-color--3b85d9, #3B85D9);
  stop-opacity: 0;
}

.qj4xl8b8v {
  stop-color: var(--svg-color--46daff, #46DAFF);
  stop-opacity: 0;
}

.qyxrx7qcu {
  stop-color: var(--svg-color--3a83b9, #3A83B9);
}

.r_mr1sqsb {
  stop-color: var(--svg-color--4acfec, #4ACFEC);
  stop-opacity: 0;
}

.r3498vbtj {
  stop-color: var(--svg-color--4cd1ff, #4CD1FF);
}

.ro5r6cc4i {
  stop-color: var(--svg-color--3777af, #3777AF);
}

.senet9b-v {
  stop-color: var(--svg-color--59e7ff, #59E7FF);
}

.th052uhjh {
  fill: var(--svg-color--1c93e9, #1C93E9);
  d: path("M11.48 14.01c-.16 0-.32-.07-.42-.21a.527.527 0 0 1 .1-.74c.06-.05 1.48-1.12 3.59-.87c.29.03.5.3.46.59c-.03.29-.3.5-.59.46c-1.65-.2-2.81.65-2.82.66c-.1.07-.21.11-.32.11");
}

.trfkg6bth {
  fill: var(--svg-color--38b6e3, #38B6E3);
  d: path("M26.48 18.54c-.04 0-.17.01-.21.01A2.76 2.76 0 0 0 23.8 17a2.78 2.78 0 0 0-2.78 2.78c0 .546.161 1.052.437 1.48c.279.432.395 1.004.06 1.392c-.643.742-1.528 1.41-2.717 1.638c-.2.04-.24.3-.07.41c.7.44 2.12 1.17 3.93 1.32a1.445 1.445 0 0 0 2.878.097a.17.17 0 0 1 .195-.15a3.6 3.6 0 0 0 .647.063a3.74 3.74 0 0 0 3.74-3.74c0-2.06-1.57-3.75-3.64-3.75");
}

.u8f82jbbs {
  stop-color: var(--svg-color--4f9cf1, #4F9CF1);
}

.uingq-bue {
  stop-color: var(--svg-color--3591bf, #3591BF);
}

.v__1ogpqq {
  stop-color: var(--svg-color--34a2c9, #34A2C9);
  stop-opacity: 0;
}

.v5id5xm0y {
  stop-color: var(--svg-color--5ff5ff, #5FF5FF);
}

.vdysjzt7h {
  d: path("M23.672 24.566a1.342 1.342 0 0 0 .455 2.604c.67 0 1.267-.492 1.338-1.382c-.415-.852-1.227-1.149-1.793-1.222");
}

.vnoz_qbee {
  stop-color: var(--svg-color--3999e8, #3999E8);
}

.wfchz7fwt {
  stop-color: var(--svg-color--46d8ff, #46D8FF);
  stop-opacity: 0;
}

.wszlyidlp {
  stop-color: var(--svg-color--2e80bf, #2E80BF);
  stop-opacity: 0;
}

.wvblunb8o {
  stop-color: var(--svg-color--52c1ff, #52C1FF);
}

.wwl9kxb6t {
  stop-color: var(--svg-color--52c4ff, #52C4FF);
  stop-opacity: 0;
}

.x6oe0pbyu {
  stop-color: var(--svg-color--3777af, #3777AF);
  stop-opacity: 0;
}

.x8dvo4byn {
  stop-color: var(--svg-color--5de8ff, #5DE8FF);
  stop-opacity: 0;
}

.x9wlabc9g {
  stop-color: var(--svg-color--1c7aca, #1C7ACA);
}

.xh5--389s {
  stop-color: var(--svg-color--46daff, #46DAFF);
}

.y_7gj1bsi {
  stop-color: var(--svg-color--29aced, #29ACED);
  stop-opacity: 0;
}

.y3jye8wyn {
  fill: var(--svg-color--2875bd, #2875BD);
  d: path("M11.405 14.133a.5.5 0 0 1-.41-.191a.51.51 0 0 1 .078-.716c.056-.05 1.397-1.116 3.436-.928c.28.021.49.276.458.557a.504.504 0 0 1-.556.458c-1.595-.152-2.691.696-2.7.706a.54.54 0 0 1-.306.114");
}

.y56y4oyzb {
  stop-color: var(--svg-color--4f9cf1, #4F9CF1);
  stop-opacity: 0;
}

.y86ixgbio {
  stop-color: var(--svg-color--1c7aca, #1C7ACA);
  stop-opacity: 0;
}

.yqrkw9bjm {
  stop-color: var(--svg-color--2598e2, #2598E2);
}

.zqn1_9bbj {
  d: path("M12.91 2C8.74 2 2.23 2.05 2.02 2l-.01 28c8.43 0 6.24-12.44 7.51-16.92c1.52-5.37 7.51-1.08 7.51-7.09C17.03 2.84 15.7 2 12.91 2");
}

</style>
