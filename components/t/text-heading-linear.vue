<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zyobk-bwz"/><path class="btex5sb2a"/><path class="h3s_qfbzc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-heading-linear" /></template>
<style>
.btex5sb2a {
  d: path("M19 2V22");
}

.h3s_qfbzc {
  d: path("M5 12H19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zyobk-bwz {
  d: path("M5 2V22");
}

</style>
