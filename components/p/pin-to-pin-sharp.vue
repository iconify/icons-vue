<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="t2g51nbku"/><circle class="d3jhe5bxu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pin-to-pin-sharp" /></template>
<style>
.d3jhe5bxu {
  cx: 12px;
  cy: 10px;
  r: 2.75px;
}

.t2g51nbku {
  d: path("M12 21.25h-.57l-.38-.38C8.1 18.1 4.75 14.4 4.75 10a7.25 7.25 0 0 1 14.5 0c0 4.4-3.35 8.1-6.3 10.87l-.38.38z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
