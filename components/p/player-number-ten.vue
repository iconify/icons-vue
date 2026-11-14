<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vdff0qbro"/><path class="jo-3t9vdp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:player-number-ten" /></template>
<style>
.jo-3t9vdp {
  d: path("M8.25 12.75L9.5 11.5v7m2.75-3.5a1.75 3.5 0 1 0 3.5 0a1.75 3.5 0 1 0-3.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vdff0qbro {
  d: path("M8.5 2.5q3.5 3 7 0L21.75 6l-2 4.5l-1.5-.75V21.5H5.75V9.75l-1.5.75l-2-4.5Z");
}

</style>
