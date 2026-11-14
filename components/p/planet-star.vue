<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="srupzfspc"/><path class="k7n1ib9wx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:planet-star" /></template>
<style>
.k7n1ib9wx {
  d: path("M6 15a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM18.5 2q.75 2.75 3.5 3.5q-2.75.75-3.5 3.5q-.75-2.75-3.5-3.5q2.75-.75 3.5-3.5Z");
}

.srupzfspc {
  d: path("M2 14a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
