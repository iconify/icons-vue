<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w-og12zlz"/><path class="r0s-abb2f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scooter-wheel" /></template>
<style>
.r0s-abb2f {
  d: path("M10.5 16.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM12 15V3.5m-4 0h8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w-og12zlz {
  d: path("M7 16.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

</style>
