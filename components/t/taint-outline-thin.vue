<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vt-ep0bmh"/><path class="w1nvaacaj"/><path class="ox9r9tr9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:taint-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ox9r9tr9v {
  d: path("M19 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.vt-ep0bmh {
  d: path("M3 8a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.w1nvaacaj {
  d: path("M20 3v5");
}

</style>
