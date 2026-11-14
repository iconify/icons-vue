<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ep_bwzqsu"/><path class="uhu714udj"/><path class="a0ptn1x6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sync-off" /></template>
<style>
.a0ptn1x6n {
  d: path("m9 16l3 3l-3 3M3.5 3.5l17 17");
}

.ep_bwzqsu {
  d: path("M12 5a7 7 0 0 1 6.395 9.847");
}

.uhu714udj {
  d: path("m15 2l-3 3l3 3m-3 11a7 7 0 0 1-6.395-9.847");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
