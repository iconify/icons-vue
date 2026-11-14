<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="is2rbwbhm"/><path class="ovcaeebyo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:scale-bar" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.is2rbwbhm {
  d: path("M4 11h16a1.5 1.5 0 0 1 1.5 1.5v1A1.5 1.5 0 0 1 20 15H4a1.5 1.5 0 0 1-1.5-1.5v-1A1.5 1.5 0 0 1 4 11M2.5 7v4M12 8v3m9.5-4v4");
}

.ovcaeebyo {
  fill: currentColor;
  d: path("M4 11h1.75a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5H4a1.5 1.5 0 0 1-1.5-1.5v-1A1.5 1.5 0 0 1 4 11m9.5 0h1.75a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5H13.5a1.5 1.5 0 0 1-1.5-1.5v-1a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
