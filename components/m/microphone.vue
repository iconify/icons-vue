<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i4aXUEc)"><circle fill="url(#iHvlZHb)" class="onuvhc9oe"/><circle fill="url(#iyMJD2c)" class="onuvhc9oe"/><circle fill="url(#iCDad5c)" class="onuvhc9oe"/></g><path fill="url(#iQd3Uhc)" class="qa7zhebwy"/><path fill="url(#iv2ljZb)" class="n1v_-ibzc"/><path fill="url(#iRbXdHG)" class="n1v_-ibzc"/><g filter="url(#iOC3mEc)"><path fill="url(#ilL9Nbe)" class="tblq1-bdf"/><path fill="url(#i0OLNpe)" class="tblq1-bdf"/></g><g filter="url(#ibTavXX)"><circle class="lbvdmjbol"/></g><g filter="url(#i6HSKPq)"><circle fill="url(#iY1Tivc)" class="sg-3z9y6o"/></g><defs><radialGradient id="iHvlZHb" cx="0" cy="0" r="1" gradientTransform="rotate(-88.24 20.108 -2.504)scale(11.0379)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="c6-ont44s"/><stop offset="1" class="kpn8uacxs"/></radialGradient><radialGradient id="iyMJD2c" cx="0" cy="0" r="1" gradientTransform="rotate(140.631 11.827 8.61)scale(6.306 4.91911)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="f3-kqobbs"/><stop offset="1" class="wbkj9dbif"/></radialGradient><radialGradient id="iCDad5c" cx="0" cy="0" r="1" gradientTransform="matrix(1.31249 10.15766 -10.08685 1.30334 21.931 7.514)" gradientUnits="userSpaceOnUse"><stop offset=".911" class="iuaq8gopl"/><stop offset="1" class="o9q65ybyk"/></radialGradient><radialGradient id="iRbXdHG" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59376 1.66132 -9.55095 -9.16256 24.306 10.009)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ef0_7_w1b"/><stop offset="1" class="bymswxb7t"/></radialGradient><radialGradient id="i0OLNpe" cx="0" cy="0" r="1" gradientTransform="matrix(-15.1875 11.75009 -1.53732 -1.98705 19.681 15.139)" gradientUnits="userSpaceOnUse"><stop class="fuftn1blt"/><stop offset="1" class="md2vb-bkp"/></radialGradient><linearGradient id="iQd3Uhc" x1="22.431" x2="21.556" y1="11.545" y2="12.358" gradientUnits="userSpaceOnUse"><stop class="v9z20nbfx"/><stop offset="1" class="c1k79kb5y"/></linearGradient><linearGradient id="iv2ljZb" x1="15.494" x2="26.619" y1="4.264" y2="16.264" gradientUnits="userSpaceOnUse"><stop class="lalxu4bkj"/><stop offset="1" class="ukkeavn0a"/></linearGradient><linearGradient id="ilL9Nbe" x1="14.588" x2="9.494" y1="21.951" y2="16.951" gradientUnits="userSpaceOnUse"><stop class="s-97qrjpj"/><stop offset="1" class="gnzat4efe"/></linearGradient><linearGradient id="iY1Tivc" x1="13.088" x2="14.963" y1="16.951" y2="19.326" gradientUnits="userSpaceOnUse"><stop class="y7oj0_buf"/><stop offset="1" class="gjn_zvu6x"/></linearGradient><filter id="i4aXUEc" width="15.431" height="15.431" x="14.867" y="2.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.301961 0 0 0 0 0.290196 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18367"/></filter><filter id="iOC3mEc" width="20.277" height="19.049" x="2.08" y="10.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy=".75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.490196 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18367"/></filter><filter id="ibTavXX" width="3.09" height="3.09" x="12.245" y="16.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18367" stdDeviation=".075"/></filter><filter id="i6HSKPq" width="3.09" height="2.79" x="12.354" y="16.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.847059 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18367"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.572549 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_18367" result="effect2_innerShadow_18_18367"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:microphone" /></template>
<style>
.bymswxb7t {
  stop-color: var(--svg-color--a7a0af, #A7A0AF);
  stop-opacity: 0;
}

.c1k79kb5y {
  stop-color: var(--svg-color--382a4b, #382A4B);
  stop-opacity: 0;
}

.c6-ont44s {
  stop-color: var(--svg-color--512f70, #512F70);
}

.ef0_7_w1b {
  stop-color: var(--svg-color--c9c8cb, #C9C8CB);
}

.f3-kqobbs {
  stop-color: var(--svg-color--6c6476, #6C6476);
}

.ft5dv1b6b {
  fill: none;
}

.fuftn1blt {
  stop-color: var(--svg-color--aea6b5, #AEA6B5);
}

.gjn_zvu6x {
  stop-color: var(--svg-color--cdc4d4, #CDC4D4);
}

.gnzat4efe {
  stop-color: var(--svg-color--949198, #949198);
}

.iuaq8gopl {
  stop-color: var(--svg-color--513071, #513071);
  stop-opacity: 0;
}

.kpn8uacxs {
  stop-color: var(--svg-color--372d44, #372D44);
}

.lalxu4bkj {
  stop-color: var(--svg-color--848286, #848286);
}

.lbvdmjbol {
  cx: 13.79px;
  cy: 18.087px;
  r: 1.395px;
  fill: var(--svg-color--8a858f, #8A858F);
}

.md2vb-bkp {
  stop-color: var(--svg-color--aea6b5, #AEA6B5);
  stop-opacity: 0;
}

.n1v_-ibzc {
  d: path("M16.51 3.539a1.61 1.61 0 0 1 2.273.078l9.887 10.59a1.608 1.608 0 0 1-2.35 2.194L16.433 5.81a1.61 1.61 0 0 1 .078-2.272");
}

.o9q65ybyk {
  stop-color: var(--svg-color--72538f, #72538F);
}

.onuvhc9oe {
  cx: 22.333px;
  cy: 10.206px;
  r: 7.466px;
}

.qa7zhebwy {
  d: path("M17.542 4.48a7.466 7.466 0 1 0 10.092 10.982z");
}

.s-97qrjpj {
  stop-color: var(--svg-color--ada3b3, #ADA3B3);
}

.sg-3z9y6o {
  cx: 13.899px;
  cy: 18.087px;
  r: 1.395px;
}

.tblq1-bdf {
  d: path("m14.886 10.96l6.221 6.619L5.762 28.813a2.315 2.315 0 0 1-3.134-3.364z");
}

.ukkeavn0a {
  stop-color: var(--svg-color--a89fb0, #A89FB0);
}

.v9z20nbfx {
  stop-color: var(--svg-color--382a4b, #382A4B);
}

.wbkj9dbif {
  stop-color: var(--svg-color--6c6476, #6C6476);
  stop-opacity: 0;
}

.y7oj0_buf {
  stop-color: var(--svg-color--c0bac6, #C0BAC6);
}

</style>
