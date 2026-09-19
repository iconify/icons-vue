<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iW4wa2w)"><path class="m2u2b1bmi"/></g><g filter="url(#iU5bllb)"><path fill="url(#irlxH7k)" class="k7r-th4eq"/></g><g filter="url(#ixEQfTb)"><path class="s35s4-wid"/></g><path fill="url(#iDgSBtb)" class="zwlpl_b4s"/><path fill="url(#i3Tskbc)" class="zwlpl_b4s"/><g filter="url(#iaoDsVd)"><path fill="url(#iy0dfHe)" class="kg2hwwbql"/></g><g filter="url(#iggHM1c)"><path fill="url(#i2ppiTc)" class="ce705qbwv"/><path fill="url(#iad3Q2d)" class="ce705qbwv"/></g><path fill="url(#iJAyaip)" class="ce705qbwv"/><g filter="url(#iAlzg0d)"><path fill="url(#iJpgGhd)" class="wewypdhmt"/><path fill="url(#ieLzLNb)" class="wewypdhmt"/><path fill="url(#iEoXU8c)" class="wewypdhmt"/></g><g filter="url(#iOq1JHe)"><path fill="url(#i7R9JeL)" class="n9peyub_k"/><path fill="url(#iT5Qiec)" class="n9peyub_k"/><path fill="url(#iunkFrb)" class="n9peyub_k"/></g><defs><linearGradient id="irlxH7k" x1="16.211" x2="16.211" y1="14.438" y2="29.91" gradientUnits="userSpaceOnUse"><stop class="bd016ep7i"/><stop offset="1" class="favyhut1i"/></linearGradient><linearGradient id="i3Tskbc" x1="16.211" x2="16.211" y1="26.781" y2="27.531" gradientUnits="userSpaceOnUse"><stop class="kltgicc2s"/><stop offset="1" class="u4rlf0bom"/></linearGradient><linearGradient id="iy0dfHe" x1="12.516" x2="5.266" y1="28.656" y2="21.938" gradientUnits="userSpaceOnUse"><stop offset=".75" class="jil_8xbrq"/><stop offset=".932" class="be714rkta"/></linearGradient><linearGradient id="i2ppiTc" x1="19.844" x2="27.094" y1="28.656" y2="21.938" gradientUnits="userSpaceOnUse"><stop offset=".717" class="u33qfvbvl"/><stop offset=".913" class="lh91iabfb"/></linearGradient><linearGradient id="iad3Q2d" x1="27.976" x2="27.976" y1="8.886" y2="13.327" gradientUnits="userSpaceOnUse"><stop class="r99uddckn"/><stop offset="1" class="h5cnerbhj"/></linearGradient><linearGradient id="iJAyaip" x1="16.18" x2="17.797" y1="27" y2="25.094" gradientUnits="userSpaceOnUse"><stop class="md0fzj6xl"/><stop offset="1" class="xl8xj4b2m"/></linearGradient><linearGradient id="iJpgGhd" x1="4.805" x2="15.328" y1="17.512" y2="17.512" gradientUnits="userSpaceOnUse"><stop class="t7e_x933r"/><stop offset="1" class="y542mhrfe"/></linearGradient><linearGradient id="ieLzLNb" x1="16.18" x2="13.453" y1="25.688" y2="25.688" gradientUnits="userSpaceOnUse"><stop class="dhc12dmkk"/><stop offset="1" class="ow81f1rsa"/></linearGradient><linearGradient id="iEoXU8c" x1="16.234" x2="16.016" y1="25.906" y2="25.906" gradientUnits="userSpaceOnUse"><stop offset=".179" class="eztk90ckq"/><stop offset="1" class="pz7_ubbtn"/></linearGradient><linearGradient id="i7R9JeL" x1="16.18" x2="26.703" y1="17.512" y2="17.512" gradientUnits="userSpaceOnUse"><stop class="t7e_x933r"/><stop offset="1" class="y542mhrfe"/></linearGradient><linearGradient id="iT5Qiec" x1="16.18" x2="18.984" y1="25.688" y2="25.688" gradientUnits="userSpaceOnUse"><stop class="dhc12dmkk"/><stop offset="1" class="ow81f1rsa"/></linearGradient><linearGradient id="iunkFrb" x1="16.152" x2="16.359" y1="25.906" y2="25.906" gradientUnits="userSpaceOnUse"><stop class="eztk90ckq"/><stop offset="1" class="pz7_ubbtn"/></linearGradient><filter id="iW4wa2w" width="27.916" height="19.998" x="2.328" y="10.881" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.541176 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20736"/></filter><filter id="iU5bllb" width="27.966" height="19.948" x="2.228" y="9.963" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.45098 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20736"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.666667 0 0 0 0 0.901961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_20736" result="effect2_innerShadow_18_20736"/></filter><filter id="ixEQfTb" width="26.938" height="19.055" x="2.531" y="8.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_20736" stdDeviation=".25"/></filter><filter id="iaoDsVd" width="13.069" height="18.639" x="3.211" y="8.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.705882 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20736"/></filter><filter id="iggHM1c" width="13.069" height="18.639" x="16.18" y="8.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.835294 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20736"/></filter><filter id="iAlzg0d" width="11.475" height="19.011" x="4.805" y="8.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.819608 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20736"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.976471 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_20736" result="effect2_innerShadow_18_20736"/></filter><filter id="iOq1JHe" width="11.475" height="19.011" x="16.08" y="8.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.976471 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20736"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.819608 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_20736" result="effect2_innerShadow_18_20736"/></filter><radialGradient id="iDgSBtb" cx="0" cy="0" r="1" gradientTransform="matrix(2 -1 1.40312 2.80625 15.375 28.531)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="xsmwsmbxm"/><stop offset="1" class="g-p-rmb2d"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:open-book" /></template>
<style>
.bd016ep7i {
  stop-color: var(--svg-color--5dd8fb, #5DD8FB);
}

.be714rkta {
  stop-color: var(--svg-color--b6bac5, #B6BAC5);
}

.ce705qbwv {
  d: path("M28.935 10.455L27.369 8.46L25.528 23.5H16.18V27h11.718c.69 0 1.25-.56 1.25-1.25V11.072a1 1 0 0 0-.213-.617");
}

.dhc12dmkk {
  stop-color: var(--svg-color--d5cce8, #D5CCE8);
}

.eztk90ckq {
  stop-color: var(--svg-color--bfb3d1, #BFB3D1);
}

.favyhut1i {
  stop-color: var(--svg-color--41aef2, #41AEF2);
}

.ft5dv1b6b {
  fill: none;
}

.g-p-rmb2d {
  stop-color: var(--svg-color--1a4ca8, #1A4CA8);
}

.h5cnerbhj {
  stop-color: var(--svg-color--d8dae2, #D8DAE2);
  stop-opacity: 0;
}

.jil_8xbrq {
  stop-color: var(--svg-color--b3a9cf, #B3A9CF);
}

.k7r-th4eq {
  d: path("M3.578 10.063c-.69 0-1.25.56-1.25 1.25v16.39c0 .69.56 1.25 1.25 1.25h11.005a1.863 1.863 0 0 0 3.256 0h11.005c.69 0 1.25-.56 1.25-1.25v-16.39c0-.69-.56-1.25-1.25-1.25z");
}

.kg2hwwbql {
  d: path("M3.424 10.455L4.99 8.46L6.832 23.5h9.348V27H4.46c-.69 0-1.25-.56-1.25-1.25V11.072a1 1 0 0 1 .214-.617");
}

.kltgicc2s {
  stop-color: var(--svg-color--1748a6, #1748A6);
}

.lh91iabfb {
  stop-color: var(--svg-color--dcdde8, #DCDDE8);
}

.m2u2b1bmi {
  fill: var(--svg-color--3e6aca, #3E6ACA);
  d: path("M3.578 11.031c-.69 0-1.25.56-1.25 1.25v16.39c0 .691.56 1.25 1.25 1.25h11.005a1.863 1.863 0 0 0 3.256 0h11.005c.69 0 1.25-.559 1.25-1.25v-16.39c0-.69-.56-1.25-1.25-1.25z");
}

.md0fzj6xl {
  stop-color: var(--svg-color--a699c9, #A699C9);
}

.n9peyub_k {
  d: path("M27.555 9.031a1 1 0 0 0-1-1H18.68a2.5 2.5 0 0 0-2.5 2.5v16.461c0-1.1 1.133-1.992 2.445-1.992h7.68c.69 0 1.25-.56 1.25-1.25z");
}

.ow81f1rsa {
  stop-color: var(--svg-color--f2ebff, #F2EBFF);
  stop-opacity: 0;
}

.pz7_ubbtn {
  stop-color: var(--svg-color--bfb3d1, #BFB3D1);
  stop-opacity: 0;
}

.r99uddckn {
  stop-color: var(--svg-color--d8dae2, #D8DAE2);
}

.s35s4-wid {
  fill: var(--svg-color--3f9bea, #3F9BEA);
  d: path("m4.81 9.094l-1.565 1.941a.96.96 0 0 0-.214.602V25.93c0 .672.56 1.217 1.25 1.217H27.72c.69 0 1.25-.545 1.25-1.217V11.637a.96.96 0 0 0-.214-.602L27.19 9.094L25.348 23.74H6.652z");
}

.t7e_x933r {
  stop-color: var(--svg-color--f3f1fa, #F3F1FA);
}

.u33qfvbvl {
  stop-color: var(--svg-color--bbb3d9, #BBB3D9);
}

.u4rlf0bom {
  stop-color: var(--svg-color--1748a6, #1748A6);
  stop-opacity: 0;
}

.wewypdhmt {
  d: path("M4.805 9.031a1 1 0 0 1 1-1h7.875a2.5 2.5 0 0 1 2.5 2.5v16.461c0-1.1-1.133-1.992-2.446-1.992h-7.68c-.69 0-1.25-.56-1.25-1.25z");
}

.xl8xj4b2m {
  stop-color: var(--svg-color--a699c9, #A699C9);
  stop-opacity: 0;
}

.xsmwsmbxm {
  stop-color: var(--svg-color--306ab3, #306AB3);
}

.y542mhrfe {
  stop-color: var(--svg-color--f0ebf9, #F0EBF9);
}

.zwlpl_b4s {
  d: path("M14.773 25.703h2.875v1.578a1.438 1.438 0 1 1-2.875 0z");
}

</style>
