<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2u6d4rwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rainfall-moderate" /></template>
<style>
.d2u6d4rwn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 4s-3.5 5-3.5 8a3.5 3.5 0 0 0 7 0C10.5 9 7 4 7 4Zm10 2s-3.5 5-3.5 8a3.5 3.5 0 0 0 7 0c0-3-3.5-8-3.5-8ZM5 21h14");
}

</style>
