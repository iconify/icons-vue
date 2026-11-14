<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iktsbgbfm"/><path class="e-a7jvbtf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rotation" /></template>
<style>
.e-a7jvbtf {
  d: path("M17.25 11L16 8.5l2.5-1.25");
}

.iktsbgbfm {
  d: path("M12 2.5v19M4 12a8 4 0 0 0 16 0a8 4 0 0 0-4-3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
