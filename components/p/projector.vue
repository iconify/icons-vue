<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w7krslbzl"/><path class="hlkc1bbji"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:projector" /></template>
<style>
.hlkc1bbji {
  d: path("M12.75 12a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M6 12h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w7krslbzl {
  d: path("M6.875 7h10.25a4.375 4.375 0 0 1 4.375 4.375v1.25A4.375 4.375 0 0 1 17.125 17H6.875A4.375 4.375 0 0 1 2.5 12.625v-1.25A4.375 4.375 0 0 1 6.875 7M6 17v2m12-2v2");
}

</style>
