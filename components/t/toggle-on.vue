<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dkebj3bea"/><path class="bg3rxrbif"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:toggle-on" /></template>
<style>
.bg3rxrbif {
  d: path("M13 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-5.5-1.75v3.5");
}

.dkebj3bea {
  d: path("M6 6.5h12a3.5 3.5 0 0 1 3.5 3.5v4a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 14v-4A3.5 3.5 0 0 1 6 6.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
