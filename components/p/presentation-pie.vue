<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i2biyzbmj"/><path class="o850skb0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:presentation-pie" /></template>
<style>
.i2biyzbmj {
  d: path("M2.5 2.5h19V16h-19Zm5.5 19l2-5.5m6 5.5L14 16");
}

.o850skb0w {
  d: path("M11.25 10V7a3 3 0 1 0 3 3Zm2-2V5a3 3 0 0 1 3 3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
