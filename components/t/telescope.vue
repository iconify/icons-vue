<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path stroke="url(#ixkHZKd)" class="l7pn372fp"/><path stroke="url(#iJIZ5ed)" class="rpkoifbkz"/><path stroke="url(#ia3GWmd)" class="rpkoifbkz"/><path stroke="url(#isvf6Ae)" class="rpkoifbkz"/><path stroke="url(#iw6Dx2U)" class="rpkoifbkz"/><path stroke="url(#iFVts8d)" class="tl_ciobww"/><path stroke="url(#i7LWH7c)" class="tl_ciobww"/><g filter="url(#i5PW7mb)"><path stroke="url(#i7lvXdP)" class="gg7ryhcvv"/></g><path class="lxhj86itg"/><path fill="url(#i8krccc)" class="yatdolb0f"/><path fill="url(#iq2PyDb)" class="yatdolb0f"/><path fill="url(#i8uYc3d)" class="yatdolb0f"/><path fill="url(#iSOzsXd)" class="vwjznbbld"/><path fill="url(#iPsfhte)" class="vwjznbbld"/><path fill="url(#i5RnS9b)" class="vwjznbbld"/><g filter="url(#igZMdJj)"><path class="rlvh26bhm"/></g><path fill="url(#ipGZjvc)" class="ah7f9m26r"/><path fill="url(#ifl18ne)" class="ah7f9m26r"/><g filter="url(#i43SNbd)"><rect transform="matrix(0 -1 -1 0 18.7 16.438)" class="lrgdjk6nv"/></g><rect fill="url(#i7e5O8d)" transform="matrix(0 -1 -1 0 18.7 16.438)" class="cbhjg6uha"/><rect fill="url(#ig7vnOe)" transform="matrix(0 -1 -1 0 18.7 16.438)" class="cbhjg6uha"/><g filter="url(#iFLqNVt)"><path class="n51rldj_f"/></g><g filter="url(#ihZYahd)"><path fill="url(#ivcdlyb)" class="yy1srvm_r"/></g><path fill="url(#iJ3b5Vc)" class="qn0l68n3j"/><path fill="url(#iNXGXmd)" class="qn0l68n3j"/><path fill="url(#iWqJiGd)" class="qn0l68n3j"/><g filter="url(#iAwE76b)"><path class="abhkj5u0d"/></g><g filter="url(#iYODb2N)"><path class="cfhdv1baj"/></g><defs><linearGradient id="ixkHZKd" x1="16" x2="15.137" y1="23.875" y2="23.875" gradientUnits="userSpaceOnUse"><stop class="qtknuiu-l"/><stop offset="1" class="bke1lvbwt"/></linearGradient><linearGradient id="iJIZ5ed" x1="20.902" x2="19.855" y1="20.734" y2="21.422" gradientUnits="userSpaceOnUse"><stop class="vjf_mib-i"/><stop offset="1" class="xqxed1rrq"/></linearGradient><linearGradient id="ia3GWmd" x1="16.777" x2="17.137" y1="17.516" y2="17.297" gradientUnits="userSpaceOnUse"><stop class="cn_2krbho"/><stop offset="1" class="knb62hblb"/></linearGradient><linearGradient id="iw6Dx2U" x1="17.203" x2="17.203" y1="15.422" y2="17.203" gradientUnits="userSpaceOnUse"><stop offset=".407" class="p-1keqbge"/><stop offset="1" class="mjukjbbjs"/></linearGradient><linearGradient id="iFVts8d" x1="11.496" x2="10.027" y1="23.047" y2="22.109" gradientUnits="userSpaceOnUse"><stop class="jmitipbxt"/><stop offset=".944" class="w3yti4tqa"/></linearGradient><linearGradient id="i7LWH7c" x1="14.797" x2="14.797" y1="15.438" y2="17.219" gradientUnits="userSpaceOnUse"><stop offset=".407" class="p-1keqbge"/><stop offset="1" class="mjukjbbjs"/></linearGradient><linearGradient id="i7lvXdP" x1="6.559" x2="15.41" y1="28.781" y2="15.656" gradientUnits="userSpaceOnUse"><stop offset=".743" class="vdlu6ouiw"/><stop offset="1" class="dr1ii4sru"/></linearGradient><linearGradient id="i8krccc" x1="25.684" x2="24.465" y1="11.547" y2="14.734" gradientUnits="userSpaceOnUse"><stop class="qtz1cg2yw"/><stop offset="1" class="s3tthcc6z"/></linearGradient><linearGradient id="iq2PyDb" x1="25.402" x2="25.949" y1="15.234" y2="13.594" gradientUnits="userSpaceOnUse"><stop offset=".068" class="t-u4ci-3w"/><stop offset="1" class="gjqp05b1r"/></linearGradient><linearGradient id="i8uYc3d" x1="20.237" x2="21.481" y1="12.371" y2="12.774" gradientUnits="userSpaceOnUse"><stop offset=".256" class="dnkytbckn"/><stop offset="1" class="u-dge-mni"/></linearGradient><linearGradient id="iSOzsXd" x1="29.46" x2="27.82" y1="11.22" y2="15.833" gradientUnits="userSpaceOnUse"><stop offset=".343" class="pqn4mubmy"/><stop offset="1" class="f0iu52bsf"/></linearGradient><linearGradient id="iPsfhte" x1="26.855" x2="27.432" y1="12.891" y2="13.039" gradientUnits="userSpaceOnUse"><stop class="p0k78ibdr"/><stop offset="1" class="s9m06-bla"/></linearGradient><linearGradient id="ipGZjvc" x1="13.902" x2="12.773" y1="7.203" y2="10.922" gradientUnits="userSpaceOnUse"><stop class="qtz1cg2yw"/><stop offset="1" class="s3tthcc6z"/></linearGradient><linearGradient id="ifl18ne" x1="14.402" x2="15.074" y1="12.406" y2="10.641" gradientUnits="userSpaceOnUse"><stop offset=".18" class="jlwq0ybwn"/><stop offset="1" class="gjqp05b1r"/></linearGradient><linearGradient id="iJ3b5Vc" x1="9.725" x2="7.37" y1="3.019" y2="9.511" gradientUnits="userSpaceOnUse"><stop offset=".343" class="pqn4mubmy"/><stop offset="1" class="f0iu52bsf"/></linearGradient><linearGradient id="iNXGXmd" x1="6.277" x2="6.699" y1="5.391" y2="5.547" gradientUnits="userSpaceOnUse"><stop class="p0k78ibdr"/><stop offset="1" class="s9m06-bla"/></linearGradient><linearGradient id="iWqJiGd" x1="6.327" x2="6.765" y1="9.511" y2="8.469" gradientUnits="userSpaceOnUse"><stop class="ww5mqoxns"/><stop offset="1" class="h-muprboi"/></linearGradient><filter id="i5PW7mb" width="10.403" height="14.309" x="5.607" y="15.322" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25150" stdDeviation=".2"/></filter><filter id="igZMdJj" width="7.509" height="4.647" x="20.533" y="9.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25150" stdDeviation=".5"/></filter><filter id="i43SNbd" width="5.898" height="2.734" x="12.801" y="14.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.129412 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25150"/></filter><filter id="iFLqNVt" width="14.553" height="7.212" x="8.464" y="4.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25150" stdDeviation=".5"/></filter><filter id="ihZYahd" width="5.468" height="6.953" x="2.607" y="2.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.780392 0 0 0 0 0.85098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25150"/></filter><filter id="iAwE76b" width="4.419" height="3.607" x="6.114" y="3.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25150" stdDeviation=".3"/></filter><filter id="iYODb2N" width="3.551" height="2.972" x="26.655" y="11.592" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25150" stdDeviation=".3"/></filter><radialGradient id="isvf6Ae" cx="0" cy="0" r="1" gradientTransform="matrix(-.53906 -.07812 .06241 -.43066 26.395 28.969)" gradientUnits="userSpaceOnUse"><stop offset=".274" class="bhd_4jf6v"/><stop offset="1" class="iqk6_l06c"/></radialGradient><radialGradient id="i5RnS9b" cx="0" cy="0" r="1" gradientTransform="rotate(109.312 10.24 16.914)scale(1.93712 .26624)" gradientUnits="userSpaceOnUse"><stop offset=".091" class="zqz91mb6s"/><stop offset="1" class="jv3xu6bbr"/></radialGradient><radialGradient id="i7e5O8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.07812 -2.25 0 .688 .813)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="ihs_m1baq"/><stop offset=".92" class="nwzn4tbsn"/></radialGradient><radialGradient id="ig7vnOe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.14063 -.75318 0 1.281 1.828)" gradientUnits="userSpaceOnUse"><stop class="cciiij0vr"/><stop offset="1" class="y16lz_tfm"/></radialGradient><radialGradient id="ivcdlyb" cx="0" cy="0" r="1" gradientTransform="matrix(-.96873 2.6875 -2.4817 -.89454 6.215 5.64)" gradientUnits="userSpaceOnUse"><stop offset=".224" class="v4oj9kmpt"/><stop offset="1" class="yai8dqbme"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:telescope" /></template>
<style>
.abhkj5u0d {
  fill: var(--svg-color--7468b7, #7468B7);
  d: path("m7.232 4.094l2.7.983l-.518 1.424l-2.7-.983z");
}

.ah7f9m26r {
  d: path("M2.813 4.297a3.415 3.415 0 0 1 4.376-2.044L22.874 7.95a.1.1 0 0 1 .06.128L20.67 14.31a.1.1 0 0 1-.128.06L4.857 8.673a3.415 3.415 0 0 1-2.044-4.376");
}

.bhd_4jf6v {
  stop-color: var(--svg-color--604fa8, #604FA8);
}

.bke1lvbwt {
  stop-color: var(--svg-color--605482, #605482);
}

.cbhjg6uha {
  width: 2.234px;
  height: 5.398px;
  rx: 1.117px;
}

.cciiij0vr {
  stop-color: var(--svg-color--574775, #574775);
}

.cfhdv1baj {
  fill: var(--svg-color--7266b6, #7266B6);
  d: path("m27.64 12.192l1.967.716l-.384 1.055l-1.967-.716z");
}

.cn_2krbho {
  stop-color: var(--svg-color--574c77, #574C77);
}

.dnkytbckn {
  stop-color: var(--svg-color--734497, #734497);
}

.dr1ii4sru {
  stop-color: var(--svg-color--6250a3, #6250A3);
  stop-opacity: 0;
}

.f0iu52bsf {
  stop-color: var(--svg-color--503398, #503398);
}

.ft5dv1b6b {
  fill: none;
}

.gg7ryhcvv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m15.41 15.922l-9.203 13.11");
}

.gjqp05b1r {
  stop-color: var(--svg-color--987bb3, #987BB3);
  stop-opacity: 0;
}

.h-muprboi {
  stop-color: var(--svg-color--7b64ae, #7B64AE);
  stop-opacity: 0;
}

.ihs_m1baq {
  stop-color: var(--svg-color--614f7b, #614F7B);
  stop-opacity: 0;
}

.iqk6_l06c {
  stop-color: var(--svg-color--604fa8, #604FA8);
  stop-opacity: 0;
}

.jlwq0ybwn {
  stop-color: var(--svg-color--8e69b0, #8E69B0);
}

.jmitipbxt {
  stop-color: var(--svg-color--5640a6, #5640A6);
}

.jv3xu6bbr {
  stop-color: var(--svg-color--7d72be, #7D72BE);
  stop-opacity: 0;
}

.knb62hblb {
  stop-color: var(--svg-color--574c77, #574C77);
  stop-opacity: 0;
}

.l7pn372fp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("M16 16v12.984");
}

.lrgdjk6nv {
  width: 2.234px;
  height: 5.398px;
  fill: var(--svg-color--431670, #431670);
  rx: 1.117px;
}

.lxhj86itg {
  fill: var(--svg-color--251350, #251350);
  d: path("M15.371 11.563h1.258v3.531h-1.258z");
}

.mjukjbbjs {
  stop-color: var(--svg-color--1d0a4a, #1D0A4A);
  stop-opacity: 0;
}

.n51rldj_f {
  fill: var(--svg-color--c9c2d2, #C9C2D2);
  d: path("m9.733 5.143l12.284 4.472l-.269.74L9.464 5.883z");
}

.nwzn4tbsn {
  stop-color: var(--svg-color--614f7b, #614F7B);
}

.p-1keqbge {
  stop-color: var(--svg-color--1d0a4a, #1D0A4A);
}

.p0k78ibdr {
  stop-color: var(--svg-color--533a9a, #533A9A);
}

.pqn4mubmy {
  stop-color: var(--svg-color--7166b3, #7166B3);
}

.qn0l68n3j {
  d: path("M10.762 3.55L7.488 2.362l-2.332 6.42l3.274 1.19z");
}

.qtknuiu-l {
  stop-color: var(--svg-color--3c1681, #3C1681);
}

.qtz1cg2yw {
  stop-color: var(--svg-color--c1c0c1, #C1C0C1);
}

.rlvh26bhm {
  fill: var(--svg-color--c9c2d2, #C9C2D2);
  d: path("m21.802 10.109l5.24 1.907l-.27.74l-5.24-1.907z");
}

.rpkoifbkz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("m16.59 15.922l9.203 13.11");
}

.s3tthcc6z {
  stop-color: var(--svg-color--9777b3, #9777B3);
}

.s9m06-bla {
  stop-color: var(--svg-color--5d47a3, #5D47A3);
  stop-opacity: 0;
}

.t-u4ci-3w {
  stop-color: var(--svg-color--864eb1, #864EB1);
}

.tl_ciobww {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("M15.41 15.938L6.207 29.047");
}

.u-dge-mni {
  stop-color: var(--svg-color--734497, #734497);
  stop-opacity: 0;
}

.v4oj9kmpt {
  stop-color: var(--svg-color--addeff, #ADDEFF);
}

.vdlu6ouiw {
  stop-color: var(--svg-color--6250a3, #6250A3);
}

.vjf_mib-i {
  stop-color: var(--svg-color--5b4da4, #5B4DA4);
}

.vwjznbbld {
  d: path("m26.164 15.417l1.693-4.662l1.857.675a.75.75 0 0 1 .45.96l-1.182 3.253a.75.75 0 0 1-.961.449z");
}

.w3yti4tqa {
  stop-color: var(--svg-color--43356a, #43356A);
}

.ww5mqoxns {
  stop-color: var(--svg-color--7b64ae, #7B64AE);
}

.xqxed1rrq {
  stop-color: var(--svg-color--423174, #423174);
}

.y16lz_tfm {
  stop-color: var(--svg-color--574775, #574775);
  stop-opacity: 0;
}

.yai8dqbme {
  stop-color: var(--svg-color--a2cffb, #A2CFFB);
}

.yatdolb0f {
  d: path("M30.163 12.39a.75.75 0 0 0-.449-.96l-8.568-3.113l-1.693 4.663l8.568 3.112a.75.75 0 0 0 .96-.45z");
}

.yy1srvm_r {
  d: path("M8.074 2.58L5.742 9l-.885-.327a3.415 3.415 0 1 1 2.332-6.42z");
}

.zqz91mb6s {
  stop-color: var(--svg-color--7d72be, #7D72BE);
}

</style>
