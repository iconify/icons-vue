<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mi_t_0lml"/><path class="bndmef82d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:succulent" /></template>
<style>
.bndmef82d {
  d: path("M12 15c-4 0-7-3-8-6.5c3.75.5 6.5 2.5 8 6.5Zm0 0c4 0 7-3 8-6.5c-3.75.5-6.5 2.5-8 6.5Z");
}

.mi_t_0lml {
  d: path("M6.5 15h11l-1.25 6h-8.5Zm5.5 0c-2-3-2-8.5 0-12c2 3.5 2 9 0 12Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
