<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iVe1jPb)"><rect fill="url(#in38yBA)" class="re33ppmrn"/><rect fill="url(#iIWy1Dd)" class="re33ppmrn"/></g><g filter="url(#iMqFLfc)"><path stroke="url(#iFuLzTc)" class="aenlmebmx"/></g><g filter="url(#idOfJ9c)"><path stroke="url(#i1mR8Zd)" class="ur97ctb7j"/></g><g filter="url(#iLzCf8d)"><path class="wiqd734ck"/></g><g filter="url(#i5heV9b)"><path class="s-2n2sb3q"/></g><defs><filter id="iVe1jPb" width="28.875" height="28.875" x="2.09" y=".688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.133333 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2436"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.168627 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2436" result="effect2_innerShadow_18590_2436"/></filter><filter id="iMqFLfc" width="5.5" height="28.375" x="25.528" y="1.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2436" stdDeviation="1"/></filter><filter id="idOfJ9c" width="27.281" height="5.5" x="2.804" y=".75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2436" stdDeviation="1"/></filter><filter id="iLzCf8d" width="13.953" height="20" x="9.048" y="5.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2436" stdDeviation=".5"/></filter><filter id="i5heV9b" width="12.753" height="18.8" x="9.648" y="6.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.886275 0 0 0 0 0.968627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2436"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2436" result="effect2_innerShadow_18590_2436"/></filter><linearGradient id="in38yBA" x1="16.028" x2="16.028" y1="5.262" y2="38.515" gradientUnits="userSpaceOnUse"><stop class="guv2pdl6x"/><stop offset="1" class="p6sc0mbpz"/></linearGradient><linearGradient id="iFuLzTc" x1="28.778" x2="28.778" y1="4.188" y2="27.063" gradientUnits="userSpaceOnUse"><stop class="cc4pv5b4k"/><stop offset="1" class="wcjb-1bar"/></linearGradient><linearGradient id="i1mR8Zd" x1="28.492" x2="2.96" y1="3.75" y2="3.75" gradientUnits="userSpaceOnUse"><stop class="d_ud1bcih"/><stop offset="1" class="g4-_dqiwv"/></linearGradient><radialGradient id="iIWy1Dd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.747 3.781)" gradientUnits="userSpaceOnUse"><stop class="z100lacuo"/><stop offset="1" class="smhn3ex5m"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:o-button-blood-type" /></template>
<style>
.aenlmebmx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.278 4.188v22.875");
}

.cc4pv5b4k {
  stop-color: var(--svg-color--ff66a5, #FF66A5);
}

.d_ud1bcih {
  stop-color: var(--svg-color--ff60a3, #FF60A3);
}

.ft5dv1b6b {
  fill: none;
}

.g4-_dqiwv {
  stop-color: var(--svg-color--ff5495, #FF5495);
}

.guv2pdl6x {
  stop-color: var(--svg-color--ff4d91, #FF4D91);
}

.p6sc0mbpz {
  stop-color: var(--svg-color--f34a5f, #F34A5F);
}

.re33ppmrn {
  width: 27.875px;
  height: 27.875px;
  x: 2.09px;
  y: 1.688px;
  rx: 3.6px;
}

.s-2n2sb3q {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M10.048 12.602a5.977 5.977 0 1 1 11.953 0v6.046a5.977 5.977 0 1 1-11.953 0zm5.976-2.977a2.977 2.977 0 0 0-2.976 2.977v6.046a2.977 2.977 0 0 0 5.953 0v-6.046a2.977 2.977 0 0 0-2.977-2.977");
}

.smhn3ex5m {
  stop-color: var(--svg-color--ff77b1, #FF77B1);
  stop-opacity: 0;
}

.ur97ctb7j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.554 3.5h21.781");
}

.wcjb-1bar {
  stop-color: var(--svg-color--ff5b6b, #FF5B6B);
}

.wiqd734ck {
  fill: var(--svg-color--ef2b54, #EF2B54);
  d: path("M10.048 12.602a5.977 5.977 0 1 1 11.953 0v6.046a5.977 5.977 0 1 1-11.953 0zm5.976-2.977a2.977 2.977 0 0 0-2.976 2.977v6.046a2.977 2.977 0 0 0 5.953 0v-6.046a2.977 2.977 0 0 0-2.977-2.977");
}

.z100lacuo {
  stop-color: var(--svg-color--ff77b1, #FF77B1);
}

</style>
