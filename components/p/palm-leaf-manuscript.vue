<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbjejjbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:palm-leaf-manuscript" /></template>
<style>
.gbjejjbpp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 4.5h14A1.5 1.5 0 0 1 20.5 6A1.5 1.5 0 0 1 19 7.5H5A1.5 1.5 0 0 1 3.5 6A1.5 1.5 0 0 1 5 4.5m0 6h14a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H5A1.5 1.5 0 0 1 3.5 12A1.5 1.5 0 0 1 5 10.5m0 6h14a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H5A1.5 1.5 0 0 1 3.5 18A1.5 1.5 0 0 1 5 16.5m7-14v19");
}

</style>
