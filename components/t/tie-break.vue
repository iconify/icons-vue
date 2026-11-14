<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f38kfxpdo"/><path class="yhv83emwc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tie-break" /></template>
<style>
.f38kfxpdo {
  d: path("M3.75 4.75a3.5 4.5-45 1 1 6.5 6.5a3.5 4.5-45 1 1-6.5-6.5m6.5 6.5L19 20");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yhv83emwc {
  d: path("M20.25 4.75a3.5 4.5 45 1 1-6.5 6.5a3.5 4.5 45 1 1 6.5-6.5m-6.5 6.5L5 20m-.5-9.5l5-5m5 0l5 5");
}

</style>
