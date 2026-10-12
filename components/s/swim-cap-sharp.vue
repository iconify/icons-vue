<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nkjpnnb7v"/><path class="h9dg4t8hh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:swim-cap-sharp" /></template>
<style>
.h9dg4t8hh {
  d: path("M6.5 13H10v2.75H6.5zm7.5 0h3.5v2.75H14zM3.25 14.375H6.5m3.5 0h4m3.5 0h3.25");
}

.nkjpnnb7v {
  d: path("M3.25 17.25v-3.5a8.75 8.75 0 0 1 17.5 0v5H3.25zM12 5v5.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
