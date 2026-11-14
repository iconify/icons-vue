<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="crx0zaceu"/><path class="c3qc_xvjh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:molecule-space-filling" /></template>
<style>
.c3qc_xvjh {
  d: path("M7 12.25a4 4 0 1 1 5-5m3 1a3 3 0 1 1 2 4m-9 3a2.5 2.5 0 1 0 4 2");
}

.crx0zaceu {
  d: path("M7 12.25a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
