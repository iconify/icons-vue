<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cbhcelb-u"/><path class="a6xe3-c2f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scroll-to-bottom" /></template>
<style>
.a6xe3-c2f {
  d: path("M9.25 12.25L12 15l2.75-2.75M8 18.5h8");
}

.cbhcelb-u {
  d: path("M4.5 2.5h15v19h-15Zm3.5 4h8m-4 3V15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
