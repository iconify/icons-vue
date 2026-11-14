<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aet9i5ila"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:milk-carton" /></template>
<style>
.aet9i5ila {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 9L9 4h6l3.5 5v10a2 2 0 0 1-2 2h-9a2 2 0 0 1-2-2Zm0 0h13M9 4v5");
}

</style>
