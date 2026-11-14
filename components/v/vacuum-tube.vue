<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wixxmolyr"/><path class="gk6llfbgc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vacuum-tube" /></template>
<style>
.gk6llfbgc {
  d: path("M9.5 15.5v-6h5v6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wixxmolyr {
  d: path("M6.5 18.5V9a5.5 5.5 0 0 1 11 0v9.5Zm3 0v3m5-3v3");
}

</style>
