<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ezb6udbhb"/><path class="gtt0hx49y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:roc-curve-sharp" /></template>
<style>
.ezb6udbhb {
  d: path("M3.25 3.25v17.5h17.5M6.5 17.5l2-1.75m2-1.75l2-1.75m2-1.75L16 9.2");
}

.gtt0hx49y {
  d: path("M6.5 17.25C7 9.5 10.25 6.5 19.25 6");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
