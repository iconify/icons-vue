<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kk_gz9o8o"/><path class="uwmpbukkr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:time-forward-sharp" /></template>
<style>
.kk_gz9o8o {
  d: path("M20.25 12a8.25 8.25 0 1 1-2.42-5.83l2.42 2.08");
}

.uwmpbukkr {
  d: path("M20.25 3.75v4.5h-4.5M12 7.75V12l-3 1.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
