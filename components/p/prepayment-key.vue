<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uxtluvbuc"/><path class="n_p-64byt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:prepayment-key" /></template>
<style>
.n_p-64byt {
  d: path("M5.25 8.25h5.5v7.5h-5.5Zm0 3.75h5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uxtluvbuc {
  d: path("M3.5 5.5h9a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1h-9a1 1 0 0 1-1-1v-11a1 1 0 0 1 1-1Zm10 6.5h7.75M18 12v3.25M21.25 12v3.25");
}

</style>
