<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c0umfvbsr"/><path class="pzhnuqbnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sample-cup" /></template>
<style>
.c0umfvbsr {
  d: path("M5 8h14l-1 11a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 6 19ZM4 4.5h16V8H4Z");
}

.pzhnuqbnz {
  d: path("M8.5 11.5h7v5h-7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
