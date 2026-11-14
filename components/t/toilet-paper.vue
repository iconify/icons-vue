<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iw3vjjbpe"/><path class="n0s37qbiu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:toilet-paper" /></template>
<style>
.iw3vjjbpe {
  d: path("M3 9.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

.n0s37qbiu {
  d: path("M8 4.5h8a5 5 0 0 1 5 5v11h-8v-6H8m0-5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
