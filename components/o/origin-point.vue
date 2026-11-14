<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yqs324a2e"/><path class="y6ntahxml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:origin-point" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y6ntahxml {
  fill: currentColor;
  d: path("M10 9.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.yqs324a2e {
  d: path("M12 21.5s6.5-6 6.5-12a6.5 6.5 0 0 0-13 0c0 6 6.5 12 6.5 12Z");
}

</style>
