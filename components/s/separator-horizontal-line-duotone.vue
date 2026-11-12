<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yy2_6bfra"/><path class="xdk9_oksp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:separator-horizontal-line-duotone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xdk9_oksp {
  d: path("M2 12L22 12");
}

.yy2_6bfra {
  d: path("M18 15L12 21L6 15M18 9L12 3L6 9");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
