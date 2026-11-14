<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k35p1dbvj"/><path class="sm3uksbzq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stability-ball" /></template>
<style>
.k35p1dbvj {
  d: path("M3.5 11.5a8.5 8.5 0 1 0 17 0a8.5 8.5 0 1 0-17 0Z");
}

.sm3uksbzq {
  d: path("M4.5 8c4.5 3 10.5 3 15 0M7 21.5h10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
