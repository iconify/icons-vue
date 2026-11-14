<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kl5gg1bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tooltip-right" /></template>
<style>
.kl5gg1bfj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 4.5H16a2 2 0 0 1 2 2v3l3.5 2.5l-3.5 2.5v3a2 2 0 0 1-2 2H4.5a2 2 0 0 1-2-2v-11a2 2 0 0 1 2-2Zm2 5.5H14m-7.5 4H11");
}

</style>
