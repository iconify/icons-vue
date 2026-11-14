<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u1weepbfx"/><path class="nl9xh03ib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tooth-bonded" /></template>
<style>
.nl9xh03ib {
  d: path("M14 4.25Q14.75 8 19.5 8.5");
}

.u1weepbfx {
  d: path("M12 6c-1.5-1.75-3.5-2.5-5.25-2c-2 .6-2.5 2.75-2.25 5c.25 2.5 1.5 4 2.25 6.5l1 4.5c.25 1 1.75 1 2 0l1-4c.25-1 2.25-1 2.5 0l1 4c.25 1 1.75 1 2 0l1-4.5c.75-2.5 2-4 2.25-6.5c.25-2.25-.25-4.4-2.25-5c-1.75-.5-3.75.25-5.25 2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
