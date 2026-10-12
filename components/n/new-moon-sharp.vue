<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="s-q6e0b1m"/><path class="sn-dgzbyt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:new-moon-sharp" /></template>
<style>
.s-q6e0b1m {
  cx: 10.5px;
  cy: 13.5px;
  r: 7.5px;
}

.sn-dgzbyt {
  d: path("M7.92 17.19a4.5 4.5 0 0 1 0-7.38M19 2.75l.27 1.98l1.98.27l-1.98.27L19 7.25l-.27-1.98L16.75 5l1.98-.27z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
