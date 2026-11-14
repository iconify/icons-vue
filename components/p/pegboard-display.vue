<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o05zfl9jd"/><path class="nzhirrbjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pegboard-display" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nzhirrbjp {
  d: path("M11 10.75h2a.5.5 0 0 1 .5.5a.5.5 0 0 1-.5.5h-2a.5.5 0 0 1-.5-.5a.5.5 0 0 1 .5-.5M10.5 14h3a2.5 2.5 0 0 1 2.5 2.5a2.5 2.5 0 0 1-2.5 2.5h-3A2.5 2.5 0 0 1 8 16.5a2.5 2.5 0 0 1 2.5-2.5m-5-9.75h.01m12.99 0h.01");
}

.o05zfl9jd {
  d: path("M4.25 2.5h15.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 19.75 6H4.25A1.75 1.75 0 0 1 2.5 4.25A1.75 1.75 0 0 1 4.25 2.5M12 6v5.25M7.625 9h8.75A2.625 2.625 0 0 1 19 11.625v7.25a2.625 2.625 0 0 1-2.625 2.625h-8.75A2.625 2.625 0 0 1 5 18.875v-7.25A2.625 2.625 0 0 1 7.625 9");
}

</style>
