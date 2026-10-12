<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="jus0noe8b"/><path class="liqkfyb5a"/><path class="j7r0nebrr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:space-helmet-visor-sharp" /></template>
<style>
.j7r0nebrr {
  d: path("m9 10.25l.9-1.5h1.85M7.5 21.25h9");
}

.jus0noe8b {
  cx: 12px;
  cy: 10.75px;
  r: 8px;
}

.liqkfyb5a {
  d: path("M6.5 9.75C6.5 8 8.95 6.5 12 6.5s5.5 1.5 5.5 3.25v1c0 3.1-2.45 5.25-5.5 5.25s-5.5-2.15-5.5-5.25Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
