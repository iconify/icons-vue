<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxdfibbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:zero-turn-mower" /></template>
<style>
.rxdfibbhs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 17.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm13.5 2a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM3 10.75h11.5l5.5 3.5m-16-3.5L5 4h3m4.5 6.75l3-5.75H18");
}

</style>
