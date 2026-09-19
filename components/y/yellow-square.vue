<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iBhiCDc)"><path fill="url(#iCrQ3Sd)" class="uxgsmd1pz"/></g><defs><linearGradient id="iCrQ3Sd" x1="16" x2="16" y1="2" y2="30" gradientUnits="userSpaceOnUse"><stop class="h87l-jtqg"/><stop offset="1" class="rj6koacut"/></linearGradient><filter id="iBhiCDc" width="30" height="28.75" x="1" y="1.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.886275 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_3158"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.384314 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_3158" result="effect2_innerShadow_18590_3158"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.541176 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18590_3158" result="effect3_innerShadow_18590_3158"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:yellow-square" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h87l-jtqg {
  stop-color: var(--svg-color--ffd045, #FFD045);
}

.rj6koacut {
  stop-color: var(--svg-color--ff8f5f, #FF8F5F);
}

.uxgsmd1pz {
  d: path("M2 4a2 2 0 0 1 2-2h24a2 2 0 0 1 2 2v24a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2z");
}

</style>
