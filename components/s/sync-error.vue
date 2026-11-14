<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xtcd7qbnh"/><path class="qnssq-bxq"/><path class="wosba2btx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sync-error" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qnssq-bxq {
  d: path("M15 6.25h2.75V3.5M20 12a8 8 0 0 1-13.75 5.75");
}

.wosba2btx {
  d: path("M9 17.75H6.25v2.75m3.25-11l5 5m0-5l-5 5");
}

.xtcd7qbnh {
  d: path("M4 12a8 8 0 0 1 13.75-5.75");
}

</style>
