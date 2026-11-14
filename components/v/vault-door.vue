<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g6ulkabjn"/><path class="c7nf6lbdz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vault-door" /></template>
<style>
.c7nf6lbdz {
  d: path("M8.25 12a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0ZM13 12h.01M13 12V7.25M13 12l4 2.25M13 12l-4 2.25M5.5 6v2.5m0 7V18");
}

.g6ulkabjn {
  d: path("M2.5 2.5h19v19h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
