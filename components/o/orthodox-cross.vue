<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iPEc01d)"><rect fill="url(#iP1p6ge)" class="f832b9w-o"/><rect fill="url(#iuxiSae)" class="f832b9w-o"/></g><g filter="url(#ij5bKFc)"><path stroke="url(#i2vZUKb)" class="yxej9q13k"/></g><g filter="url(#iQOriUI)"><path stroke="url(#ipPfplW)" class="ty7ohqbnk"/></g><g filter="url(#izOMQsc)"><path class="w3618_6qg"/></g><g filter="url(#iYsbsqe)"><path class="h3xad6-cn"/></g><defs><filter id="iPEc01d" width="29.875" height="28.875" x="2.512" y=".813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.235294 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1066"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.211765 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1066" result="effect2_innerShadow_18590_1066"/></filter><filter id="ij5bKFc" width="5.5" height="28.375" x="25.95" y="1.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1066" stdDeviation="1"/></filter><filter id="iQOriUI" width="27.281" height="5.5" x="3.226" y=".875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1066" stdDeviation="1"/></filter><filter id="izOMQsc" width="16" height="22" x="8.867" y="4.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1066" stdDeviation=".5"/></filter><filter id="iYsbsqe" width="14.8" height="20.8" x="9.467" y="5.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.886275 0 0 0 0 0.968627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1066"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1066" result="effect2_innerShadow_18590_1066"/></filter><linearGradient id="iP1p6ge" x1="16.45" x2="16.45" y1="5.387" y2="38.64" gradientUnits="userSpaceOnUse"><stop class="sn77b5ppw"/><stop offset="1" class="fitiklbqp"/></linearGradient><linearGradient id="i2vZUKb" x1="29.2" x2="29.2" y1="4.313" y2="27.188" gradientUnits="userSpaceOnUse"><stop class="ygaxn_bkp"/><stop offset="1" class="s-kusnt3y"/></linearGradient><linearGradient id="ipPfplW" x1="28.914" x2="3.382" y1="3.875" y2="3.875" gradientUnits="userSpaceOnUse"><stop class="ka-x5u-uy"/><stop offset="1" class="jlbvuvbtx"/></linearGradient><radialGradient id="iuxiSae" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 28.169 3.906)" gradientUnits="userSpaceOnUse"><stop class="mgmxs0b3v"/><stop offset="1" class="sefcefa1m"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:orthodox-cross" /></template>
<style>
.f832b9w-o {
  width: 27.875px;
  height: 27.875px;
  x: 2.512px;
  y: 1.813px;
  rx: 3.6px;
}

.fitiklbqp {
  stop-color: var(--svg-color--7764c6, #7764C6);
}

.ft5dv1b6b {
  fill: none;
}

.h3xad6-cn {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M16.867 5.75a1 1 0 0 0-1 1v.9a.1.1 0 0 1-.1.1h-1.9a1 1 0 1 0 0 2h1.9a.1.1 0 0 1 .1.1v1.8a.1.1 0 0 1-.1.1h-4.9a1 1 0 1 0 0 2h4.9a.1.1 0 0 1 .1.1v4.882a.1.1 0 0 1-.15.086l-.984-.568a1 1 0 0 0-1 1.732l2.084 1.203a.1.1 0 0 1 .05.087v3.478a1 1 0 1 0 2 0v-2.208a.1.1 0 0 1 .15-.087l1.778 1.027a1 1 0 1 0 1-1.732l-2.878-1.662a.1.1 0 0 1-.05-.086V13.85a.1.1 0 0 1 .1-.1h4.9a1 1 0 1 0 0-2h-4.9a.1.1 0 0 1-.1-.1v-1.8a.1.1 0 0 1 .1-.1h1.9a1 1 0 1 0 0-2h-1.9a.1.1 0 0 1-.1-.1v-.9a1 1 0 0 0-1-1");
}

.jlbvuvbtx {
  stop-color: var(--svg-color--9a6ceb, #9A6CEB);
}

.ka-x5u-uy {
  stop-color: var(--svg-color--a672ff, #A672FF);
}

.mgmxs0b3v {
  stop-color: var(--svg-color--bb8dff, #BB8DFF);
}

.s-kusnt3y {
  stop-color: var(--svg-color--8777d6, #8777D6);
}

.sefcefa1m {
  stop-color: var(--svg-color--bb8dff, #BB8DFF);
  stop-opacity: 0;
}

.sn77b5ppw {
  stop-color: var(--svg-color--9865ee, #9865EE);
}

.ty7ohqbnk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.976 3.625h21.781");
}

.w3618_6qg {
  fill: var(--svg-color--6a4ebe, #6A4EBE);
  d: path("M16.867 5.75a1 1 0 0 0-1 1v.9a.1.1 0 0 1-.1.1h-1.9a1 1 0 1 0 0 2h1.9a.1.1 0 0 1 .1.1v1.8a.1.1 0 0 1-.1.1h-4.9a1 1 0 1 0 0 2h4.9a.1.1 0 0 1 .1.1v4.882a.1.1 0 0 1-.15.086l-.984-.568a1 1 0 0 0-1 1.732l2.084 1.203a.1.1 0 0 1 .05.087v3.478a1 1 0 1 0 2 0v-2.208a.1.1 0 0 1 .15-.087l1.778 1.027a1 1 0 1 0 1-1.732l-2.878-1.662a.1.1 0 0 1-.05-.086V13.85a.1.1 0 0 1 .1-.1h4.9a1 1 0 1 0 0-2h-4.9a.1.1 0 0 1-.1-.1v-1.8a.1.1 0 0 1 .1-.1h1.9a1 1 0 1 0 0-2h-1.9a.1.1 0 0 1-.1-.1v-.9a1 1 0 0 0-1-1");
}

.ygaxn_bkp {
  stop-color: var(--svg-color--ae7eff, #AE7EFF);
}

.yxej9q13k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.7 4.313v22.875");
}

</style>
