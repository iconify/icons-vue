<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iZGAwuc)"><rect fill="url(#ixN2VKc)" class="vxfo4ub_s"/></g><rect fill="url(#izo5Tfc)" class="vxfo4ub_s"/><g filter="url(#i3vYeAe)"><rect fill="url(#iUCNfhb)" class="khp5_fwbd"/></g><defs><linearGradient id="ixN2VKc" x1="16.126" x2="16.126" y1="2.42" y2="30.011" gradientUnits="userSpaceOnUse"><stop class="j5comhbxz"/><stop offset="1" class="betz77blw"/></linearGradient><linearGradient id="izo5Tfc" x1="31.505" x2="28.178" y1="28.605" y2="28.541" gradientUnits="userSpaceOnUse"><stop offset=".455" class="e8-xsfb4o"/><stop offset="1" class="cvmdusbcb"/></linearGradient><linearGradient id="iUCNfhb" x1="16.125" x2="16.125" y1="8.316" y2="26.732" gradientUnits="userSpaceOnUse"><stop class="b-lnwd1rb"/><stop offset="1" class="twe5ryl-l"/></linearGradient><filter id="iZGAwuc" width="29.521" height="28.771" x="1.365" y="1.239" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.647059 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2957"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.988235 0 0 0 0 0.972549 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2957" result="effect2_innerShadow_18590_2957"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.501961 0 0 0 0 0.678431 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18590_2957" result="effect3_innerShadow_18590_2957"/></filter><filter id="i3vYeAe" width="22.613" height="22.613" x="4.644" y="4.869" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.552941 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18590_2957"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18590_2957" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.419608 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18590_2957"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18590_2957" result="effect3_innerShadow_18590_2957"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.152941 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_18590_2957" result="effect4_innerShadow_18590_2957"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:white-square-button" /></template>
<style>
.b-lnwd1rb {
  stop-color: var(--svg-color--58456e, #58456E);
}

.betz77blw {
  stop-color: var(--svg-color--ac94c4, #AC94C4);
}

.cvmdusbcb {
  stop-color: var(--svg-color--d9d0e3, #D9D0E3);
  stop-opacity: 0;
}

.e8-xsfb4o {
  stop-color: var(--svg-color--d9d0e3, #D9D0E3);
}

.ft5dv1b6b {
  fill: none;
}

.j5comhbxz {
  stop-color: var(--svg-color--e0dae7, #E0DAE7);
}

.khp5_fwbd {
  width: 21.463px;
  height: 21.463px;
  x: 5.394px;
  y: 5.269px;
  rx: 0.5px;
}

.twe5ryl-l {
  stop-color: var(--svg-color--473c54, #473C54);
}

.vxfo4ub_s {
  width: 28.021px;
  height: 28.021px;
  x: 2.115px;
  y: 1.989px;
  rx: 2px;
}

</style>
