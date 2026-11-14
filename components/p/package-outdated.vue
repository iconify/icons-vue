<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ewnj8k68h"/><path class="uctlnx46b"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:package-outdated" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.ewnj8k68h {
  d: path("M11.985 19.037L11 19.5l-8.5-4v-9l8.5-4l8.5 4v5.606");
}

.uctlnx46b {
  d: path("m2.5 6.5l8.5 4l8.5-4m-8.5 4v9m3.75-1.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
