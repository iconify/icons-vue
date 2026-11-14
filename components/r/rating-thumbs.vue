<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tq83mcjdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rating-thumbs" /></template>
<style>
.tq83mcjdo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 6.75L7.75 3.5c.5-.75 1.75-.5 1.75.5L9 6h2.75a1 1 0 0 1 1 1L12 10.5a1 1 0 0 1-1 .75H6Zm-2.25 0v4.5m14.25 6l-1.75 3.25c-.5.75-1.75.5-1.75-.5l.5-2h-2.75a1 1 0 0 1-1-1l.75-3.5a1 1 0 0 1 1-.75h5Zm2.25-4.5v4.5");
}

</style>
