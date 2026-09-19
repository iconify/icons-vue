<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#iCh9g6d)" class="d2kvgvbvc"><path class="a0c3tmbut"/><path fill="url(#ieksYPd)" class="z94kscccy"/><path fill="url(#iCsk8Kb)" class="z94kscccy"/></g><g filter="url(#ifkbGzd)"><path class="f9vdr9ava"/><path fill="url(#iE5Nsdd)" class="bcu4frb1c"/></g><defs><radialGradient id="ieksYPd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.05217 .54509 -.62824 -1.21268 8.02 2.57)" gradientUnits="userSpaceOnUse"><stop class="hm5ojhmrf"/><stop offset="1" class="g-cgq4b_x"/></radialGradient><radialGradient id="iCsk8Kb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.8116 -.78443 .433 -1.55195 8.176 17.976)" gradientUnits="userSpaceOnUse"><stop class="rodok5rft"/><stop offset="1" class="p_tx7jbep"/></radialGradient><filter id="iCh9g6d" width="2.65" height="28.212" x="6.276" y="1.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.415686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4_7853"/></filter><filter id="ifkbGzd" width="20.647" height="15.521" x="6.026" y="3.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.745098 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4_7853"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.705882 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4_7853" result="effect2_innerShadow_4_7853"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".15"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.988235 0 0 0 0 0.976471 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4_7853" result="effect3_innerShadow_4_7853"/></filter><linearGradient id="iE5Nsdd" x1="6.691" x2="11.39" y1="13.1" y2="13.1" gradientUnits="userSpaceOnUse"><stop class="y36l7v1nh"/><stop offset="1" class="jawy_62ae"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:white-flag" /></template>
<style>
.a0c3tmbut {
  fill: var(--svg-color--9d9da2, #9D9DA2);
  d: path("M7.226 2.144a.95.95 0 0 1 .95.95v25.812a.95.95 0 0 1-1.9 0V3.094a.95.95 0 0 1 .95-.95");
}

.bcu4frb1c {
  d: path("M9.451 5.313a7.9 7.9 0 0 0-2.593-.5c-.344-.002-.582.288-.582.631v12.198a.52.52 0 0 0 .515.512c2.315.049 2.846.909 5.493.909c2.833 0 6.008-1.907 8.748-1.907c1.857 0 3.875.685 5.016 1.198c.241.108.525-.064.525-.329V5.688a.74.74 0 0 0-.425-.67c-5.097-2.338-7.6-.774-10.72.107c-1.992.563-3.766.828-5.977.188");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.f9vdr9ava {
  fill: var(--svg-color--e8e4ec, #E8E4EC);
  d: path("M9.451 5.313a7.9 7.9 0 0 0-2.593-.5c-.344-.002-.582.288-.582.631v12.198a.52.52 0 0 0 .515.512c2.315.049 2.846.909 5.493.909c2.833 0 6.008-1.907 8.748-1.907c1.857 0 3.875.685 5.016 1.198c.241.108.525-.064.525-.329V5.688a.74.74 0 0 0-.425-.67c-5.097-2.338-7.6-.774-10.72.107c-1.992.563-3.766.828-5.977.188");
}

.ft5dv1b6b {
  fill: none;
}

.g-cgq4b_x {
  stop-color: var(--svg-color--a9aaad, #A9AAAD);
  stop-opacity: 0;
}

.hm5ojhmrf {
  stop-color: var(--svg-color--a9aaad, #A9AAAD);
}

.jawy_62ae {
  stop-color: var(--svg-color--e8e4ec, #E8E4EC);
  stop-opacity: 0;
}

.p_tx7jbep {
  stop-color: var(--svg-color--64616d, #64616D);
  stop-opacity: 0;
}

.rodok5rft {
  stop-color: var(--svg-color--64616d, #64616D);
}

.y36l7v1nh {
  stop-color: var(--svg-color--c7c1cd, #C7C1CD);
}

.z94kscccy {
  d: path("M7.226 2.144a.95.95 0 0 1 .95.95v25.812a.95.95 0 0 1-1.9 0V3.094a.95.95 0 0 1 .95-.95");
}

</style>
