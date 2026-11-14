<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f7ah9zbgl"/><path class="g-ve0db2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:security-hsm" /></template>
<style>
.f7ah9zbgl {
  d: path("M8.5 5h7A3.5 3.5 0 0 1 19 8.5v7a3.5 3.5 0 0 1-3.5 3.5h-7A3.5 3.5 0 0 1 5 15.5v-7A3.5 3.5 0 0 1 8.5 5M9 2.5V5m3-2.5V5m3-2.5V5M9 19v2.5m3-2.5v2.5m3-2.5v2.5M2.5 9H5m-2.5 6H5m14-6h2.5M19 15h2.5");
}

.g-ve0db2y {
  d: path("M7.5 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m4 0h4M14 12v2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
