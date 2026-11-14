<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g2cf6ezlq"/><path class="kvk83nbzx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:retail-unit-to-let" /></template>
<style>
.g2cf6ezlq {
  d: path("M3 6.5L4.5 3h15L21 6.5m-18 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0m-8.2 15H4.5V11h15v3.8m-12 .7l2.5-2");
}

.kvk83nbzx {
  d: path("M13.75 17.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4 0H22m-2 0V20m2-2.25v1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
