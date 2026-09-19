<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iD7uXDd)"><rect fill="url(#iV0559c)" transform="rotate(45 8.542 1.2)" class="r5berzisc"/></g><path class="bffnonb-g"/><defs><linearGradient id="iV0559c" x1="24.33" x2="24.33" y1="1.201" y2="11.682" gradientUnits="userSpaceOnUse"><stop class="seoe9hqcx"/><stop offset="1" class="g_dqqsj0n"/></linearGradient><filter id="iD7uXDd" width="28.475" height="28.475" x="1.762" y="1.833" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.596078 0 0 0 0 0.658824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23242"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.909804 0 0 0 0 0.92549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23242" result="effect2_innerShadow_18_23242"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:straight-ruler" /></template>
<style>
.bffnonb-g {
  fill: var(--svg-color--9d73e8, #9D73E8);
  d: path("M11.117 3.776L9.172 5.72a.544.544 0 0 1-.77-.77l1.945-1.945zm1.492 1.491l.77.77l-1.112 1.11a.544.544 0 1 1-.77-.769zm2.216 2.217l.77.77l-1.875 1.875a.545.545 0 0 1-.77-.77zm2.281 2.28l.77.77l-1.15 1.15a.544.544 0 0 1-.77-.77zm2.248 2.249l.77.77l-1.87 1.868a.544.544 0 1 1-.769-.77zm2.268 2.267l.77.77l-1.143 1.143a.544.544 0 1 1-.77-.77zm2.212 2.212l.77.77l-1.9 1.9a.544.544 0 0 1-.77-.77zm2.253 2.253l.77.77l-1.162 1.162a.544.544 0 1 1-.77-.77zm2.273 2.274l.77.77l-1.881 1.88a.544.544 0 0 1-.77-.77z");
}

.ft5dv1b6b {
  fill: none;
}

.g_dqqsj0n {
  stop-color: var(--svg-color--bab8c0, #BAB8C0);
}

.r5berzisc {
  width: 31.576px;
  height: 10.482px;
  x: 8.542px;
  y: 1.201px;
  rx: 2.25px;
}

.seoe9hqcx {
  stop-color: var(--svg-color--cac8d1, #CAC8D1);
}

</style>
