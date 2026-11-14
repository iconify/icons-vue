<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r06vt4cok"/><path class="nieedoghr"/><path class="iff670b6y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:maintenance-cart" /></template>
<style>
.iff670b6y {
  d: path("M6 10h9v5.5H6Zm2.5 0V7.75h4V10M18 5a2 2 0 1 0 3.5 0m-1.75 3l-.5 7.5");
}

.nieedoghr {
  d: path("M5 17.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm8.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.r06vt4cok {
  d: path("M3 8.5v7h18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
