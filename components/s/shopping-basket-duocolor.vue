<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uyl8pnj4k"/><path class="p6-8oi2cz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-basket-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p6-8oi2cz {
  d: path("M3 10h18M4 10l2 8c.294 1.175 1.118 2 2 2h8c.882 0 1.706-.825 2-2l2-8m-10 0v10m4-10v10");
}

.uyl8pnj4k {
  stroke-opacity: 0.4;
  d: path("m5 10l4-6m10 6l-4-6");
}

</style>
