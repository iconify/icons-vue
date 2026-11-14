<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ogb3_-b4g"/><path class="qfv0rmi_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:microfiber-cloth" /></template>
<style>
.ogb3_-b4g {
  d: path("M5 3h14a2 2 0 0 1 2 2v8q-5 0-8 8H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2Z");
}

.qfv0rmi_j {
  d: path("M21 13q-1 5.5-8 8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
