<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dw2ryo68h"/><path class="lhvhjnx9p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:terminal-sudo" /></template>
<style>
.dw2ryo68h {
  d: path("M11.4 18H2.5V3.5h18v8.7");
}

.lhvhjnx9p {
  d: path("m6 6.5l3 3l-3 3m5 0h3m4 1.75l3.75 1.5V18c0 2-1.5 3.25-3.75 4c-2.25-.75-3.75-2-3.75-4v-2.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
