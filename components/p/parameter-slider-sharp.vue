<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="s88z3cf6n"/><circle class="l48-m7blu"/><path class="wke8hi1lr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:parameter-slider-sharp" /></template>
<style>
.l48-m7blu {
  cx: 8px;
  cy: 7.5px;
  r: 2.5px;
}

.s88z3cf6n {
  d: path("M2.75 7.5h2.5m5.5 0h10.5m-18.5 9H12m7.75 0h1.5");
}

.wke8hi1lr {
  d: path("M15.75 12.75q.45 3.3 3.75 3.75q-3.3.45-3.75 3.75q-.45-3.3-3.75-3.75q3.3-.45 3.75-3.75Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
