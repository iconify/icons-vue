<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arbuol-mq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:routine-run" /></template>
<style>
.arbuol-mq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6A2.25 2.25 0 1 0 7 6a2.25 2.25 0 1 0-4.5 0Zm7.25 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM17 6a2.25 2.25 0 1 0 4.5 0A2.25 2.25 0 1 0 17 6ZM7 6h2.75m4.5 0H17m-2 7.5l6.5 4l-6.5 4Z");
}

</style>
