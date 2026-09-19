<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iJ0U4vb)"><rect fill="url(#i6Stozd)" class="ubh4kgb_o"/><rect fill="url(#iI3yrEb)" class="ubh4kgb_o"/></g><g filter="url(#iO7C1wL)"><path stroke="url(#iXF6cge)" class="vw9g392bb"/></g><g filter="url(#iXadSeb)"><path stroke="url(#iugaGab)" class="t3z01ipwg"/></g><g filter="url(#iBdm2KC)"><path class="wm6a4bcku"/></g><g filter="url(#iQmr1ce)"><path class="pba15vm0x"/></g><defs><filter id="iJ0U4vb" width="28.875" height="28.875" x="2.066" y=".813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_722"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_722" result="effect2_innerShadow_18590_722"/></filter><filter id="iO7C1wL" width="5.5" height="28.375" x="25.503" y="1.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_722" stdDeviation="1"/></filter><filter id="iXadSeb" width="27.281" height="5.5" x="2.78" y=".875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_722" stdDeviation="1"/></filter><filter id="iBdm2KC" width="20.112" height="14.63" x="6.364" y="8.435" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_722" stdDeviation=".5"/></filter><filter id="iQmr1ce" width="19.112" height="13.63" x="6.764" y="9.035" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.854902 0 0 0 0 0.980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_722"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_722" result="effect2_innerShadow_18590_722"/></filter><linearGradient id="i6Stozd" x1="16.003" x2="16.003" y1="5.387" y2="38.64" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="iXF6cge" x1="28.753" x2="28.753" y1="4.313" y2="27.188" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="iugaGab" x1="28.467" x2="2.936" y1="3.875" y2="3.875" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="iI3yrEb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.722 3.906)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:right-arrow" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k8tg0e93k {
  stop-color: var(--svg-color--5db6ff, #5DB6FF);
}

.mqmvrj28a {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
}

.pba15vm0x {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M25.197 16.443a1 1 0 0 0 0-1.386l-5.112-5.313c-.625-.649-1.72-.207-1.72.693V13.5a.25.25 0 0 1-.25.25h-9.75a1 1 0 0 0-1 1v2a1 1 0 0 0 1 1h9.75a.25.25 0 0 1 .25.25v3.063c0 .9 1.096 1.342 1.72.693z");
}

.pjb-fs-ow {
  stop-color: var(--svg-color--4878dd, #4878DD);
}

.pttsnab-v {
  stop-color: var(--svg-color--7dd8ff, #7DD8FF);
}

.t3z01ipwg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.53 3.625h21.78");
}

.tcol3199r {
  stop-color: var(--svg-color--5cb7ff, #5CB7FF);
}

.tzz9ercjs {
  stop-color: var(--svg-color--639df4, #639DF4);
}

.ubh4kgb_o {
  width: 27.875px;
  height: 27.875px;
  x: 2.066px;
  y: 1.813px;
  rx: 3.6px;
}

.v8b118b2b {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
  stop-opacity: 0;
}

.vw9g392bb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.253 4.313v22.875");
}

.wm6a4bcku {
  fill: var(--svg-color--579fff, #579FFF);
  d: path("M25.197 16.443a1 1 0 0 0 0-1.386l-5.112-5.313c-.625-.649-1.72-.207-1.72.693V13.5a.25.25 0 0 1-.25.25h-9.75a1 1 0 0 0-1 1v2a1 1 0 0 0 1 1h9.75a.25.25 0 0 1 .25.25v3.063c0 .9 1.096 1.342 1.72.693z");
}

.xaz-kzbvq {
  stop-color: var(--svg-color--7fd9ff, #7FD9FF);
}

</style>
