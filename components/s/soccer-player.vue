<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gkn4aqbvk"/><path class="jg0_c_1zv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:soccer-player" /></template>
<style>
.gkn4aqbvk {
  d: path("M7.5 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm1.25 5L8 14l-3.5 7M8 14l4.75 2");
}

.jg0_c_1zv {
  d: path("m5 12l3.75-3L13 11.5m2 7.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
