<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pmpp6sbta"/><path class="f8xczgbia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pickup-point-sharp" /></template>
<style>
.f8xczgbia {
  d: path("M9 7.25h6v5.5H9zm3 0V9");
}

.pmpp6sbta {
  d: path("M12 2.75a7.5 7.5 0 0 1 7.5 7.5c0 6.05-7.5 11-7.5 11s-7.5-4.95-7.5-11a7.5 7.5 0 0 1 7.5-7.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
