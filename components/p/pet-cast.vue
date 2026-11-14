<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gip4fkbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-cast" /></template>
<style>
.gip4fkbjq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 10.25H7a2.5 2.5 0 1 0-4 0q1.5 1.75 0 3.5a2.5 2.5 0 1 0 4 0h3.25m3.5-3.5H17a2.5 2.5 0 1 1 4 0q-1.5 1.75 0 3.5a2.5 2.5 0 1 1-4 0h-3.25m-3.5-6.25h3.5v9h-3.5Z");
}

</style>
