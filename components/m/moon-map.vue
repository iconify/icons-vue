<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mey21abvb"/><path class="kd_9hk0ly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:moon-map" /></template>
<style>
.kd_9hk0ly {
  d: path("M15 7.75a5 5 0 1 0 0 8.5a5 5 0 0 1 0-8.5Zm-4.5 2.75h.01m-.01 3h.01");
}

.mey21abvb {
  d: path("m3 5l6-2l6 2l6-2v16l-6 2l-6-2l-6 2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
