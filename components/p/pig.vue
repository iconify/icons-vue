<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path class="spd3qubxl"/><path fill="url(#i0droCc)" class="j19w-ablq"/><path fill="url(#iMxcBDd)" class="j19w-ablq"/><path fill="url(#iAUEjQT)" class="j19w-ablq"/><path fill="url(#ivJvOBb)" class="j19w-ablq"/><path fill="url(#iTpD7kn)" class="nlllkvbxw"/><path fill="url(#ise3HRb)" class="qhlxxz3we"/><path fill="url(#iw58GiU)" class="dwmcfg0zw"/><path fill="url(#i3BP3bc)" class="dwmcfg0zw"/><path fill="url(#iM0eVoe)" class="dwmcfg0zw"/><path fill="url(#i7VBnPy)" class="dwmcfg0zw"/><path fill="url(#iiLZD6B)" class="dwmcfg0zw"/><path fill="url(#iI8foPI)" class="dwmcfg0zw"/><path fill="url(#iuOTRvb)" class="dwmcfg0zw"/><path fill="url(#iG2fQUb)" class="dwmcfg0zw"/><path fill="url(#iGeEy2d)" class="dwmcfg0zw"/><path fill="url(#i4c24Vc)" class="cjl6_pbgq"/><path fill="url(#iRCHGxe)" class="zl-5n72hw"/><path fill="url(#ieyb2lb)" class="zl-5n72hw"/><path fill="url(#iMwvZcL)" class="zl-5n72hw"/><path fill="url(#i2BwFhd)" class="zl-5n72hw"/><g filter="url(#iKwvTob)"><path class="o5ihz6b1u"/></g><path fill="url(#ipDorIc)" class="swg5snupd"/><path fill="url(#iBjmHYd)" class="swg5snupd"/><path fill="url(#ilAix8c)" class="swg5snupd"/><g filter="url(#iF6Uv8d)"><ellipse fill="url(#iRagZcc)" transform="rotate(-31.82 24.927 15.581)" class="mq-qejl_o"/></g><g filter="url(#iDJPJTd)"><path fill="url(#iBAntNb)" class="r0df_wbri"/></g><g filter="url(#iJF64bM)"><path fill="url(#igZbHCD)" class="d602-fbzo"/></g></g><defs><linearGradient id="i0droCc" x1="30" x2="30" y1="15.256" y2="12.475" gradientUnits="userSpaceOnUse"><stop class="l07ctcy_c"/><stop offset="1" class="n9n_69b-a"/></linearGradient><linearGradient id="iAUEjQT" x1="27.656" x2="29" y1="12.631" y2="12.319" gradientUnits="userSpaceOnUse"><stop class="xd2yg9bdv"/><stop offset="1" class="n9sv98bsm"/></linearGradient><linearGradient id="iw58GiU" x1="16" x2="16" y1="8.5" y2="28.662" gradientUnits="userSpaceOnUse"><stop class="vl9ee4qav"/><stop offset="0" class="eitxogb0o"/><stop offset="1" class="vl9ee4qav"/></linearGradient><linearGradient id="i3BP3bc" x1="18.688" x2="18.688" y1="24" y2="10.875" gradientUnits="userSpaceOnUse"><stop class="n19ni4bjo"/><stop offset="1" class="da6-prbgd"/></linearGradient><linearGradient id="i4c24Vc" x1="19.125" x2="19.125" y1="23.5" y2="25.881" gradientUnits="userSpaceOnUse"><stop offset=".239" class="wh4olwdzx"/><stop offset="1" class="w0zn_bbyi"/></linearGradient><linearGradient id="iRCHGxe" x1="3" x2="3" y1="14.52" y2="21.537" gradientUnits="userSpaceOnUse"><stop class="acsb9l8ux"/><stop offset="1" class="wf0v_4vnh"/></linearGradient><linearGradient id="ieyb2lb" x1="2.331" x2="2.331" y1="21.149" y2="18.975" gradientUnits="userSpaceOnUse"><stop class="i2fti5chh"/><stop offset="1" class="vbxedvbyl"/></linearGradient><linearGradient id="iMwvZcL" x1="3" x2="3" y1="13.6" y2="15.131" gradientUnits="userSpaceOnUse"><stop class="ypqwpgixp"/><stop offset="1" class="cyd9aunjz"/></linearGradient><linearGradient id="i2BwFhd" x1="1.531" x2="2.422" y1="18.334" y2="18.334" gradientUnits="userSpaceOnUse"><stop offset=".27" class="khszmf97h"/><stop offset="1" class="w8ibhrdyi"/></linearGradient><linearGradient id="ipDorIc" x1="7.839" x2="7.226" y1="16.5" y2="16.5" gradientUnits="userSpaceOnUse"><stop class="kfeabacio"/><stop offset=".855" class="co-foyhmg"/></linearGradient><linearGradient id="iBjmHYd" x1="8.156" x2="8.156" y1="17.725" y2="16.999" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="ilAix8c" x1="6.79" x2="7.242" y1="16.622" y2="16.622" gradientUnits="userSpaceOnUse"><stop class="kfeabacio"/><stop offset="1" class="c_lfom8in"/></linearGradient><linearGradient id="iBAntNb" x1="28.07" x2="28.032" y1="28.084" y2="19.6" gradientUnits="userSpaceOnUse"><stop class="mchut7mkj"/><stop offset="1" class="samgvvtxs"/></linearGradient><linearGradient id="igZbHCD" x1="6.813" x2="10.524" y1="7.1" y2="10.198" gradientUnits="userSpaceOnUse"><stop class="i56mruzgg"/><stop offset="1" class="glomnkbey"/></linearGradient><radialGradient id="iMxcBDd" cx="0" cy="0" r="1" gradientTransform="matrix(1.71875 -1 1.6755 2.87978 27.594 13.6)" gradientUnits="userSpaceOnUse"><stop offset=".379" class="zybsjzepw"/><stop offset="1" class="pbgwz9zkc"/></radialGradient><radialGradient id="ivJvOBb" cx="0" cy="0" r="1" gradientTransform="rotate(-28.238 37.22 -53.386)scale(.95773 1.89326)" gradientUnits="userSpaceOnUse"><stop class="xbd7vg9qi"/><stop offset="1" class="uy726vxbg"/></radialGradient><radialGradient id="iTpD7kn" cx="0" cy="0" r="1" gradientTransform="matrix(-.71876 3.90624 -.98363 -.181 21.656 26.656)" gradientUnits="userSpaceOnUse"><stop class="oe_7ej6ch"/><stop offset="1" class="oo8u1pb_v"/></radialGradient><radialGradient id="ise3HRb" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 3.875 -.97575 .18099 16.781 26.594)" gradientUnits="userSpaceOnUse"><stop class="oe_7ej6ch"/><stop offset="1" class="oo8u1pb_v"/></radialGradient><radialGradient id="iM0eVoe" cx="0" cy="0" r="1" gradientTransform="rotate(-50.001 24.872 6.254)scale(3.54904 2.15645)" gradientUnits="userSpaceOnUse"><stop class="sucrs-bby"/><stop offset="1" class="da6-prbgd"/></radialGradient><radialGradient id="i7VBnPy" cx="0" cy="0" r="1" gradientTransform="matrix(-6.75 5.12501 -6.3246 -8.32994 33.688 10.037)" gradientUnits="userSpaceOnUse"><stop class="wzadw4fmm"/><stop offset="1" class="zsx3mbmkb"/></radialGradient><radialGradient id="iiLZD6B" cx="0" cy="0" r="1" gradientTransform="rotate(-44.165 31.446 4.101)scale(3.79005 3.09584)" gradientUnits="userSpaceOnUse"><stop class="ez5d_f80u"/><stop offset=".777" class="azuvfzm6j"/></radialGradient><radialGradient id="iI8foPI" cx="0" cy="0" r="1" gradientTransform="matrix(3.6875 3.8125 -4.67801 4.52464 3.125 12.6)" gradientUnits="userSpaceOnUse"><stop class="ez5d_f80u"/><stop offset=".777" class="azuvfzm6j"/></radialGradient><radialGradient id="iuOTRvb" cx="0" cy="0" r="1" gradientTransform="rotate(-137.539 19.53 6.39)scale(4.49012 8.98622)" gradientUnits="userSpaceOnUse"><stop class="ez5d_f80u"/><stop offset="1" class="azuvfzm6j"/></radialGradient><radialGradient id="iG2fQUb" cx="0" cy="0" r="1" gradientTransform="matrix(2.625 -2.5625 2.8206 2.8894 9.531 27.037)" gradientUnits="userSpaceOnUse"><stop class="i6ik744ec"/><stop offset="1" class="azuvfzm6j"/></radialGradient><radialGradient id="iGeEy2d" cx="0" cy="0" r="1" gradientTransform="matrix(2.01563 .125 -.25278 4.07614 5.813 10.6)" gradientUnits="userSpaceOnUse"><stop class="g8rtvb-9q"/><stop offset="1" class="c7liubx9o"/></radialGradient><radialGradient id="iRagZcc" cx="0" cy="0" r="1" gradientTransform="rotate(171.019 13.187 8.868)scale(4.83012 4.43445)" gradientUnits="userSpaceOnUse"><stop class="f-3sfb6ln"/><stop offset="1" class="pbuqrygno"/></radialGradient><filter id="iKwvTob" width="1.813" height="2.753" x="6.788" y="15.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3020" stdDeviation=".25"/></filter><filter id="iF6Uv8d" width="10.846" height="12.174" x="19.503" y="9.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3020" stdDeviation=".5"/></filter><filter id="iDJPJTd" width="1.891" height="7.688" x="26.359" y="21.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3020" stdDeviation=".25"/></filter><filter id="iJF64bM" width="5.544" height="3.2" x="5.838" y="8.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3020" stdDeviation=".3"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pig" /></template>
<style>
.acsb9l8ux {
  stop-color: var(--svg-color--fac5be, #FAC5BE);
}

.aztbnnbvp {
  stop-color: var(--svg-color--552d52, #552D52);
}

.azuvfzm6j {
  stop-color: var(--svg-color--f28677, #F28677);
  stop-opacity: 0;
}

.c_lfom8in {
  stop-color: var(--svg-color--574d50, #574D50);
  stop-opacity: 0;
}

.c7liubx9o {
  stop-color: var(--svg-color--ff9ead, #FF9EAD);
  stop-opacity: 0;
}

.cjl6_pbgq {
  d: path("M13 24.34v1.16h10.67c0-1.01-.82-2-1.82-2h-8.01c-.46 0-.84.38-.84.84");
}

.co-foyhmg {
  stop-color: var(--svg-color--31232c, #31232C);
}

.cyd9aunjz {
  stop-color: var(--svg-color--e7bbb1, #E7BBB1);
  stop-opacity: 0;
}

.d602-fbzo {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("m8.406 11.069l-1.969-2H8.25l2.531 2z");
}

.da6-prbgd {
  stop-color: var(--svg-color--ff5c97, #FF5C97);
  stop-opacity: 0;
}

.dwmcfg0zw {
  d: path("M22 9.5c-3.943 0-7.886.01-11.828.01c-.316 0-.605-.159-.84-.37A2.52 2.52 0 0 0 7.66 8.5H5.95c-.4 0-.64.45-.41.78l1.254 1.856a.52.52 0 0 1-.075.663A8.1 8.1 0 0 0 5.14 13.98c-.15.32-.48.52-.83.52H2.94c-.52 0-.94.42-.94.94v4.12c0 .52.42.94.94.94h1.42c.41 0 .81.16 1.1.46l4.86 4.85c.17.17.68.556.68 1.587v1.793c0 .17.14.31.31.31h1.38c.17 0 .31-.14.31-.31V25.5h10.684l.691.46c.39.296 1.625 1.046 1.625 2.609v.621c0 .17.14.31.31.31h1.38c.17 0 .31-.14.31-.31v-6.023c0-.243.09-.476.242-.666A7.998 7.998 0 0 0 22 9.5");
}

.eitxogb0o {
  stop-color: var(--svg-color--fcaeb1, #FCAEB1);
}

.ez5d_f80u {
  stop-color: var(--svg-color--f28677, #F28677);
}

.f-3sfb6ln {
  stop-color: var(--svg-color--ffbdc4, #FFBDC4);
}

.ft5dv1b6b {
  fill: none;
}

.g8rtvb-9q {
  stop-color: var(--svg-color--ff9ead, #FF9EAD);
}

.glomnkbey {
  stop-color: var(--svg-color--ffd7db, #FFD7DB);
  stop-opacity: 0;
}

.i2fti5chh {
  stop-color: var(--svg-color--e398c7, #E398C7);
}

.i56mruzgg {
  stop-color: var(--svg-color--ffd7db, #FFD7DB);
}

.i6ik744ec {
  stop-color: var(--svg-color--ffa194, #FFA194);
}

.j19w-ablq {
  d: path("M28 10.87v6.63h2v-4.82c0-.99-.61-1.83-1.48-2.17c-.25-.1-.52.09-.52.36");
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.kfeabacio {
  stop-color: var(--svg-color--574d50, #574D50);
}

.khszmf97h {
  stop-color: var(--svg-color--f3d7d4, #F3D7D4);
}

.l07ctcy_c {
  stop-color: var(--svg-color--ff8a95, #FF8A95);
}

.mchut7mkj {
  stop-color: var(--svg-color--ff7f8d, #FF7F8D);
}

.mq-qejl_o {
  cx: 24.927px;
  cy: 15.581px;
  rx: 3.952px;
  ry: 5.46px;
}

.n19ni4bjo {
  stop-color: var(--svg-color--ff5c97, #FF5C97);
}

.n9n_69b-a {
  stop-color: var(--svg-color--ff8e99, #FF8E99);
  stop-opacity: 0;
}

.n9sv98bsm {
  stop-color: var(--svg-color--fa6e74, #FA6E74);
  stop-opacity: 0;
}

.nlllkvbxw {
  d: path("M22.94 24.5h-2L20 29.14c-.03.19.12.36.31.36h1.37c.15 0 .28-.11.31-.26z");
}

.o5ihz6b1u {
  fill: var(--svg-color--db5f79, #DB5F79);
  d: path("M7.695 17.377c-.228 0-.407-.193-.407-.439v-.876c0-.246.18-.439.407-.439c.228 0 .407.193.407.439v.876c0 .246-.18.439-.407.439");
}

.oe_7ej6ch {
  stop-color: var(--svg-color--ff83a0, #FF83A0);
}

.oo8u1pb_v {
  stop-color: var(--svg-color--ed5388, #ED5388);
}

.pbgwz9zkc {
  stop-color: var(--svg-color--fb6c72, #FB6C72);
  stop-opacity: 0;
}

.pbuqrygno {
  stop-color: var(--svg-color--ffbdc4, #FFBDC4);
  stop-opacity: 0;
}

.qhlxxz3we {
  d: path("M15 24.5h2l.94 4.64c.03.19-.12.36-.31.36h-1.37a.32.32 0 0 1-.31-.26z");
}

.r0df_wbri {
  d: path("M26.86 21.99h.89v6.243a.445.445 0 0 1-.89 0z");
}

.samgvvtxs {
  stop-color: var(--svg-color--ff7f8d, #FF7F8D);
  stop-opacity: 0;
}

.spd3qubxl {
  fill: var(--svg-color--ffb4c8, #FFB4C8);
  d: path("M28 10.87v6.63h2v-4.82c0-.99-.61-1.83-1.48-2.17c-.25-.1-.52.09-.52.36");
}

.sucrs-bby {
  stop-color: var(--svg-color--e7447f, #E7447F);
}

.swg5snupd {
  d: path("M7.5 17.5c-.28 0-.5-.22-.5-.5v-1c0-.28.22-.5.5-.5s.5.22.5.5v1c0 .28-.22.5-.5.5");
}

.uy726vxbg {
  stop-color: var(--svg-color--ffd8e1, #FFD8E1);
  stop-opacity: 0;
}

.vbxedvbyl {
  stop-color: var(--svg-color--e398c7, #E398C7);
  stop-opacity: 0;
}

.vl9ee4qav {
  stop-color: var(--svg-color--ff8585, #FF8585);
}

.w0zn_bbyi {
  stop-color: var(--svg-color--df86c9, #DF86C9);
}

.w8ibhrdyi {
  stop-color: var(--svg-color--f3d7d4, #F3D7D4);
  stop-opacity: 0;
}

.wf0v_4vnh {
  stop-color: var(--svg-color--f8b6cd, #F8B6CD);
}

.wh4olwdzx {
  stop-color: var(--svg-color--ffb0e6, #FFB0E6);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.wzadw4fmm {
  stop-color: var(--svg-color--ffbec6, #FFBEC6);
}

.xbd7vg9qi {
  stop-color: var(--svg-color--ffe3e9, #FFE3E9);
}

.xd2yg9bdv {
  stop-color: var(--svg-color--fa6e74, #FA6E74);
}

.ypqwpgixp {
  stop-color: var(--svg-color--e7bbb1, #E7BBB1);
}

.zl-5n72hw {
  d: path("M4 19v-3c0-.75-.54-1.36-1.26-1.48c-.42.09-.74.47-.74.92v4.12c0 .45.32.83.74.92C3.46 20.36 4 19.75 4 19");
}

.zsx3mbmkb {
  stop-color: var(--svg-color--ffbec6, #FFBEC6);
  stop-opacity: 0;
}

.zybsjzepw {
  stop-color: var(--svg-color--fb6c72, #FB6C72);
}

</style>
