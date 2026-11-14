<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9b83bbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:school-sneakers" /></template>
<style>
.v9b83bbke {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16v-5c2.5 0 4-1 5-3.5l2.5 1c1 1.75 3 3 5 3.5l4.5 1c1.5.5 2 1.5 2 3v2h-19Zm0 2h19M9 11.5l2 1.5m.5-3.5l2 1.5");
}

</style>
