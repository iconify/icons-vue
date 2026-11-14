<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pgncrobni"/><path class="dddk7acpg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:report-summary" /></template>
<style>
.dddk7acpg {
  d: path("M15 6.5V9a2 2 0 0 0 2 2h2.5m-12-1H12m-4.5 2.5h9m-9 2.5H13");
}

.pgncrobni {
  d: path("M6.5 6.5H15l4.5 4.5v4.5a2 2 0 0 1-2 2h-11a2 2 0 0 1-2-2v-7a2 2 0 0 1 2-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
