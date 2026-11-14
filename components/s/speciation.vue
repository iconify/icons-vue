<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c54b0xbnb"/><path class="pt0cgubkx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:speciation" /></template>
<style>
.c54b0xbnb {
  d: path("M12 21.5V14c0-4-3-5-5.5-7.5M12 14c0-4 3-5 5.5-7.5M3 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.pt0cgubkx {
  d: path("M17 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
