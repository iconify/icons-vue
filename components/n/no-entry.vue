<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iBjTC0c)"><path fill="url(#i8jlWKc)" class="y398zwb_y"/></g><g filter="url(#iG9fM9b)"><path class="dgxrk5s_e"/></g><g filter="url(#iR8Tz4q)"><path class="qlvpxobtk"/></g><defs><filter id="iBjTC0c" width="28.9" height="28.9" x="1.202" y="1.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.466667 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_556"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.160784 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_556" result="effect2_innerShadow_18590_556"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.65"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.121569 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18590_556" result="effect3_innerShadow_18590_556"/></filter><filter id="iG9fM9b" width="22" height="6" x="4.602" y="13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_556" stdDeviation=".5"/></filter><filter id="iR8Tz4q" width="20.5" height="4.5" x="5.102" y="14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.858824 0 0 0 0 0.980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_556"/></filter><linearGradient id="i8jlWKc" x1="15.602" x2="15.602" y1="4.563" y2="30" gradientUnits="userSpaceOnUse"><stop class="ce5rgqtki"/><stop offset="1" class="z7h7zyt5f"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:no-entry" /></template>
<style>
.ce5rgqtki {
  stop-color: var(--svg-color--fe4e8e, #FE4E8E);
}

.dgxrk5s_e {
  fill: var(--svg-color--ff4d76, #FF4D76);
  d: path("M5.602 15a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-18a1 1 0 0 1-1-1z");
}

.ft5dv1b6b {
  fill: none;
}

.qlvpxobtk {
  fill: var(--svg-color--f6eeff, #F6EEFF);
  d: path("M5.602 15a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-18a1 1 0 0 1-1-1z");
}

.y398zwb_y {
  d: path("M29.602 16c0 7.732-6.268 14-14 14s-14-6.268-14-14s6.268-14 14-14s14 6.268 14 14");
}

.z7h7zyt5f {
  stop-color: var(--svg-color--ff4c57, #FF4C57);
}

</style>
