<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j50pzacih"/><path class="efoj45kjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:minify" /></template>
<style>
.efoj45kjs {
  d: path("M12.5 3.5v2A1.5 1.5 0 0 0 14 7h2M2 12h3.25M3 9.75L5.25 12L3 14.25M22 12h-3.25M21 9.75L18.75 12L21 14.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j50pzacih {
  d: path("M10 3.5h2.5L16 7v11.5a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2v-13a2 2 0 0 1 2-2");
}

</style>
