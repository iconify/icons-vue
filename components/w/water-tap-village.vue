<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mr7w6paxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:water-tap-village" /></template>
<style>
.mr7w6paxf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 2.5h4v19h-4Zm4 3h5a3 3 0 0 1 3 3v2m0 3.5S15 17 15 18.75a2.5 2.5 0 0 0 5 0C20 17 17.5 14 17.5 14Z");
}

</style>
