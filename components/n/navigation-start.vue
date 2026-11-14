<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sohq57b0j"/><path class="lel93ma5w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:navigation-start" /></template>
<style>
.lel93ma5w {
  fill: currentColor;
  d: path("m7.5 3.5l13 8.5l-13 8.5Z");
}

.sohq57b0j {
  d: path("M3.5 4v16");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
