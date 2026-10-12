<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="yermxkbpn"/><path class="lwa569b5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pitch-deck-sharp" /></template>
<style>
.lwa569b5t {
  d: path("M2.75 8.75h15.5v10.5H2.75zm4 7.5v-2m3.75 2v-4m3.75 4v-5.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yermxkbpn {
  d: path("M6.25 5.25h15v10.5");
}

</style>
