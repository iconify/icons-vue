<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tqn5ncb4x"/><path class="irf21obnb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-fuel" /></template>
<style>
.irf21obnb {
  d: path("M6.5 6h4v3.5h-4Zm7 4H16a1.5 1.5 0 0 1 1.5 1.5v5a1.5 1.5 0 0 0 3 0V7L18 4.5");
}

.tqn5ncb4x {
  d: path("M3.5 3h10v18h-10Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
