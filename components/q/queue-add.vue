<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ljcdbxvgq"/><path class="mpf6no7ir"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:queue-add" /></template>
<style>
.ljcdbxvgq {
  d: path("M7 7h14v14H7Z");
}

.mpf6no7ir {
  d: path("M3 16V5a2 2 0 0 1 2-2h11m-2 7.5v7M10.5 14h7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
