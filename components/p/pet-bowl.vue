<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ey8aseb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-bowl" /></template>
<style>
.ey8aseb_c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13.5h19l-2.5 7H5ZM15 5H9a2 2 0 1 0-3 1.75A2 2 0 1 0 9 8.5h6a2 2 0 1 0 3-1.75A2 2 0 1 0 15 5Z");
}

</style>
