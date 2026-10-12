<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="et_xc3zja"/><path class="l1tk8rgvq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:power-off-eco-sharp" /></template>
<style>
.et_xc3zja {
  d: path("M6.5 7.25a8 8 0 1 0 11 0M12 2.75v7.5");
}

.l1tk8rgvq {
  d: path("M9.25 17.25c.25-2.8 1.65-4 5.5-4c-.25 2.8-1.65 4-5.5 4Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
