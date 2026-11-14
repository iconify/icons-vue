<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pju9tccfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stack-trace" /></template>
<style>
.pju9tccfl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.5V17h8.5M4 6.5h11M4 11.75h7M12.5 17a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm3-1.5l3 3m0-3l-3 3");
}

</style>
