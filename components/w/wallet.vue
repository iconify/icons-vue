<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p0653kfju"/><path class="vaxemf0zs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wallet" /></template>
<style>
.p0653kfju {
  d: path("M3 4.5h18v15H3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vaxemf0zs {
  d: path("M21 9.5h-4a2.5 2.5 0 0 0 0 5h4");
}

</style>
