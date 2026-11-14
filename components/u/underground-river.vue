<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dgro9ib7n"/><path class="vkjzt8oaq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:underground-river" /></template>
<style>
.dgro9ib7n {
  d: path("M4 20v-7a8 8 0 0 1 16 0v7M2.5 20h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vkjzt8oaq {
  d: path("M7.5 12.5q1.5-1 3 0t3 0t3 0m-9 4q1.5-1 3 0t3 0t3 0");
}

</style>
