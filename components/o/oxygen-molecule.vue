<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5ghdhbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:oxygen-molecule" /></template>
<style>
.d5ghdhbbd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm9 0a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm-2.25-1.75h4.5m-4.5 3.5h4.5");
}

</style>
