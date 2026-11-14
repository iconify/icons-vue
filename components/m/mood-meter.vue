<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ng35sb6yg"/><path class="f0g-t_b7h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mood-meter" /></template>
<style>
.f0g-t_b7h {
  d: path("M10.5 16a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm2.75-.75l3.75-2.5");
}

.ng35sb6yg {
  d: path("M3 16a9 9 0 0 1 18 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
