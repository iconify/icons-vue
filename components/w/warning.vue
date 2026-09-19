<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iGf4KAC)"><path fill="url(#i0vWTke)" class="djkxxbb6x"/></g><g filter="url(#i6BBzic)" class="pis_q6e2y"><path class="vbwglvbhv"/></g><defs><filter id="iGf4KAC" width="29.048" height="25.008" x="1.153" y="5.429" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.45"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.996078 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_533"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.929412 0 0 0 0 0.411765 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_533" result="effect2_innerShadow_18590_533"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.564706 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18590_533" result="effect3_innerShadow_18590_533"/></filter><filter id="i6BBzic" width="3.55" height="16.7" x="13.452" y="11.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75" dy=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.145098 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_533"/></filter><linearGradient id="i0vWTke" x1="15.602" x2="15.602" y1="5.829" y2="30.437" gradientUnits="userSpaceOnUse"><stop class="w-5936dfs"/><stop offset="1" class="blfhfib5u"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:warning" /></template>
<style>
.blfhfib5u {
  stop-color: var(--svg-color--ffa956, #FFA956);
}

.djkxxbb6x {
  d: path("m14.442 6.497l-12.66 21.93c-.51.89.13 2.01 1.16 2.01h25.32c1.03 0 1.67-1.11 1.16-2.01l-12.66-21.93c-.52-.89-1.8-.89-2.32 0");
}

.ft5dv1b6b {
  fill: none;
}

.pis_q6e2y {
  fill: var(--svg-color--4a4351, #4A4351);
}

.vbwglvbhv {
  d: path("M14.202 22.135a1.4 1.4 0 1 0 2.8-.01v-9.16c0-.77-.62-1.4-1.4-1.4c-.77 0-1.4.62-1.4 1.4zm2.8 3.98a1.4 1.4 0 1 1-2.8 0a1.4 1.4 0 0 1 2.8 0");
}

.w-5936dfs {
  stop-color: var(--svg-color--ffd758, #FFD758);
}

</style>
