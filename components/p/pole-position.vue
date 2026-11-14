<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z67hl9k8p"/><path class="q1ob2-bmj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pole-position" /></template>
<style>
.q1ob2-bmj {
  d: path("M4 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm8.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm7.5 3.5v6M18 17l2-1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z67hl9k8p {
  d: path("M2.5 10V7.5L5 7l4-3h3.5l3 3L21 8v2Z");
}

</style>
