<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hkdh51b8p"/><path class="mi116-bvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:queue-ticket" /></template>
<style>
.hkdh51b8p {
  d: path("M5 2.5h14V19l-2 2l-2-2l-2 2l-2-2l-2 2l-2-2l-2 2Z");
}

.mi116-bvs {
  d: path("M14.5 6.5H10l-.5 3.75q1.125-.75 2.25-.75c1.65 0 3 1.25 3 3s-1.35 3-3 3c-1 0-1.85-.4-2.5-1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
