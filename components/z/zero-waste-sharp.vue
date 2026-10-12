<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="py337y2cj"/><path class="tl9ah9brq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:zero-waste-sharp" /></template>
<style>
.py337y2cj {
  d: path("M6.5 7.75H19l-.14 1.49l-.97 10.52l-.14 1.49H6.25l-.14-1.49l-.97-10.52L5 7.75zm-3.25-2.5h17.5m-11 0v-2.5h4.5v2.5");
}

.tl9ah9brq {
  d: path("M12 10.5c1.5 0 2.25 1.4 2.25 3.6s-.75 3.65-2.25 3.65s-2.25-1.45-2.25-3.65s.75-3.6 2.25-3.6Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
