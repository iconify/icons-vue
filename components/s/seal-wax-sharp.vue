<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ln996nb_s"/><circle class="k0kijmlyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:seal-wax-sharp" /></template>
<style>
.k0kijmlyd {
  cx: 12px;
  cy: 12.25px;
  r: 3px;
}

.ln996nb_s {
  d: path("M2.75 5.25h18.5v13.5H2.75zm0 1.5l6.7 3.85m11.8-3.85l-6.7 3.85");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
