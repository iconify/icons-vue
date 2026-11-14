<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s14oxim6m"/><path class="w8o4kqbfj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-aquarium" /></template>
<style>
.s14oxim6m {
  d: path("M12.2 17H2.5V3.5h15v5.9m-15-2.9h15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w8o4kqbfj {
  d: path("M13.026 12.026L12 11c-1.5 2-4.5 2-6 0c1.5-2 4.5-2 6 0l1.5-1.5v1.87M18 21l-2.25-3.25a3.25 3.25 0 1 1 4.5 0Z");
}

</style>
