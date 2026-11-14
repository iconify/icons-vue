<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rn-yxh0-a"/><path class="amjs3-ndg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spill" /></template>
<style>
.amjs3-ndg {
  d: path("M12.25 8.5a1.75 5.5 0 1 0 3.5 0a1.75 5.5 0 1 0-3.5 0M5.5 19.25c0-2 3.5-2.25 6-1.75c2.5-.75 9-1 9 1.5S15 21.25 12 21c-3.5.5-6.5.25-6.5-1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rn-yxh0-a {
  d: path("M14 3L4 5v7l10 2");
}

</style>
