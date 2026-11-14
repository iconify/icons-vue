<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gtz6rbb9f"/><path class="bf7eri2cz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-atm" /></template>
<style>
.bf7eri2cz {
  d: path("M6 5.5h9.5V11H6Zm1 9h5.5m5.5 7.25c-1.5-1.5-3-3-3-4.75a3 3 0 0 1 6 0c0 1.75-1.5 3.25-3 4.75Z");
}

.gtz6rbb9f {
  d: path("M14.1 21.5H3v-19h15.5v8.7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
