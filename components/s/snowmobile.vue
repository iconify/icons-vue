<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awsp_v1ry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:snowmobile" /></template>
<style>
.awsp_v1ry {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 13h11v5H3Zm2.5 0v-2.5h4l2-3H14l5.5 5.5H16m-2.5-5.5l-1-3H15m2 8.5v7m-2 0h5.5a1.5 1.5 0 0 0 1.5-1.5");
}

</style>
