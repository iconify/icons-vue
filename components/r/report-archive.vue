<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qb5j-dbwn"/><path class="mo42_9bmu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:report-archive" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mo42_9bmu {
  d: path("M13.5 2.5v3a1 1 0 0 0 1 1h3M9 10V8.5m2.5 1.5V6m2.5 4V8.75");
}

.qb5j-dbwn {
  d: path("M3.75 11.5h16.5A1.75 1.75 0 0 1 22 13.25A1.75 1.75 0 0 1 20.25 15H3.75A1.75 1.75 0 0 1 2 13.25a1.75 1.75 0 0 1 1.75-1.75M3.5 15v4.5a2 2 0 0 0 2 2h13a2 2 0 0 0 2-2V15M10 18.25h4M6.5 11.5v-7a2 2 0 0 1 2-2h5l4 4v5");
}

</style>
