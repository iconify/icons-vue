<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u617ykb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:matrix-grid" /></template>
<style>
.u617ykb4f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3.5H5.5v17H8m8-17h2.5v17H16M9.5 8h.01m4.99 0h.01M9.5 12h.01m4.99 0h.01M9.5 16h.01m4.99 0h.01");
}

</style>
