<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hn7tnnbwb"/><path class="ditgzdbdl"/><path class="agh32ylxw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:panoramic-xray" /></template>
<style>
.agh32ylxw {
  d: path("M9 8c.5 2.5 1.5 4 3 4s2.5-1.5 3-4m-3 4v3.5");
}

.ditgzdbdl {
  d: path("M5.5 8c1 5 3.5 7.5 6.5 7.5S17.5 13 18.5 8");
}

.hn7tnnbwb {
  d: path("M2.5 5h19v14h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
