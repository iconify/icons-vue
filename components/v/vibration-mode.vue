<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iLIaC8d" class="kuvv8ubxw"/></defs><g class="ft5dv1b6b"><g filter="url(#iDXGXjb)"><rect fill="url(#iIw8Ntd)" class="ejim4k58s"/><rect fill="url(#ik8lWab)" class="ejim4k58s"/></g><g filter="url(#iygzxGd)"><path stroke="url(#i4G19cd)" class="ebijbxanb"/></g><g filter="url(#iuoerde)"><path stroke="url(#ivaex1b)" class="ikfg0cchl"/></g><g filter="url(#ilJEzZd)" class="ahhfrdbnr"><use href="#iLIaC8d"/></g><g filter="url(#ias7qGc)" class="b-c38gb2l"><use href="#iLIaC8d"/></g><defs><filter id="iDXGXjb" width="29.375" height="29.375" x="1.59" y=".938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.992157 0 0 0 0 0.384314 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1638"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.32549 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1638" result="effect2_innerShadow_18590_1638"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.741176 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18590_1638" result="effect3_innerShadow_18590_1638"/></filter><filter id="iygzxGd" width="5.5" height="28.375" x="25.528" y="1.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1638" stdDeviation="1"/></filter><filter id="iuoerde" width="27.281" height="5.5" x="2.804" y="1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1638" stdDeviation="1"/></filter><filter id="ilJEzZd" width="25.963" height="20" x="3.314" y="5.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1638" stdDeviation=".5"/></filter><filter id="ias7qGc" width="24.763" height="18.8" x="3.914" y="6.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.886275 0 0 0 0 0.968627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1638"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1638" result="effect2_innerShadow_18590_1638"/></filter><linearGradient id="iIw8Ntd" x1="16.028" x2="16.028" y1="5.512" y2="38.765" gradientUnits="userSpaceOnUse"><stop class="iypgd3bwl"/><stop offset="1" class="er31aq9va"/></linearGradient><linearGradient id="i4G19cd" x1="28.778" x2="28.778" y1="4.438" y2="27.313" gradientUnits="userSpaceOnUse"><stop class="a877w8v2j"/><stop offset="1" class="nb6g_x6kz"/></linearGradient><linearGradient id="ivaex1b" x1="28.492" x2="2.96" y1="4" y2="4" gradientUnits="userSpaceOnUse"><stop class="r3p3c9byv"/><stop offset="1" class="bxh812b_g"/></linearGradient><radialGradient id="ik8lWab" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.747 4.031)" gradientUnits="userSpaceOnUse"><stop class="wq09cvqal"/><stop offset="1" class="smhn3ex5m"/><stop offset="1" class="zjf3rnb7w"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:vibration-mode" /></template>
<style>
.a877w8v2j {
  stop-color: var(--svg-color--ffce69, #FFCE69);
}

.ahhfrdbnr {
  fill: var(--svg-color--ff8a53, #FF8A53);
}

.b-c38gb2l {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
}

.bxh812b_g {
  stop-color: var(--svg-color--ffb156, #FFB156);
}

.ebijbxanb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.278 4.438v22.875");
}

.ejim4k58s {
  width: 27.875px;
  height: 27.875px;
  x: 2.09px;
  y: 1.938px;
  rx: 3.6px;
}

.er31aq9va {
  stop-color: var(--svg-color--ff7e50, #FF7E50);
}

.ft5dv1b6b {
  fill: none;
}

.ikfg0cchl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.554 3.75h21.781");
}

.iypgd3bwl {
  stop-color: var(--svg-color--ffa851, #FFA851);
}

.kuvv8ubxw {
  d: path("M10.268 8.875a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2h-8a2 2 0 0 1-2-2zm10.218.594h-8.375a.25.25 0 0 0-.25.25v12.344c0 .138.112.25.25.25h8.375a.25.25 0 0 0 .25-.25V9.719a.25.25 0 0 0-.25-.25m-13.559.495a.5.5 0 0 1 .094.7a8.3 8.3 0 0 0-1.707 5.055a8.3 8.3 0 0 0 1.943 5.349a.5.5 0 0 1-.767.642a9.3 9.3 0 0 1-2.176-5.991c0-2.128.713-4.091 1.912-5.661a.5.5 0 0 1 .7-.094m2.042 3.018a.5.5 0 0 1 .094.7a3.48 3.48 0 0 0-.716 2.122c0 .856.306 1.638.815 2.246a.5.5 0 0 1-.766.642a4.48 4.48 0 0 1-1.05-2.888c0-1.025.344-1.972.922-2.729a.5.5 0 0 1 .7-.093m14.563.7a.5.5 0 0 1 .795-.607c.578.757.922 1.704.922 2.73a4.48 4.48 0 0 1-1.05 2.887a.5.5 0 0 1-.766-.642a3.48 3.48 0 0 0 .816-2.246c0-.798-.267-1.533-.717-2.122m2.136-3.718a.5.5 0 0 0-.094.7a8.3 8.3 0 0 1 1.706 5.055a8.3 8.3 0 0 1-1.943 5.349a.5.5 0 0 0 .767.642a9.3 9.3 0 0 0 2.176-5.991a9.3 9.3 0 0 0-1.912-5.661a.5.5 0 0 0-.7-.094");
}

.nb6g_x6kz {
  stop-color: var(--svg-color--ff9c61, #FF9C61);
}

.r3p3c9byv {
  stop-color: var(--svg-color--ffc85b, #FFC85B);
}

.smhn3ex5m {
  stop-color: var(--svg-color--ff77b1, #FF77B1);
  stop-opacity: 0;
}

.wq09cvqal {
  stop-color: var(--svg-color--ffd774, #FFD774);
}

.zjf3rnb7w {
  stop-color: var(--svg-color--ffd774, #FFD774);
  stop-opacity: 0;
}

</style>
