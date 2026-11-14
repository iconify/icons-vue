<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yvmvacc7u"/><path class="gzg1_lb6t"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pot-of-gold" /></template>
<style>
.gzg1_lb6t {
  d: path("M7.25 6.25a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Zm-3 3.25a2.5 2.5 0 0 1 3-3.25m9.5 3.25a2.5 2.5 0 0 0-3-3.25M14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yvmvacc7u {
  d: path("M14.15 12.25H3V9.5h15v2.7m-13.5.05c-.75 4.25 1 8.25 6 8.25q.624 0 1.182-.081");
}

</style>
