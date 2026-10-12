<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="sek-s7kcg"/><path class="t-42a2c7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:printer-3d-sharp" /></template>
<style>
.sek-s7kcg {
  d: path("M4 21V7h16v14M12 7v4.5M7 17h10");
}

.t-42a2c7u {
  d: path("M9.25 14.5h5.5V17h-5.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
