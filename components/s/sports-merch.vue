<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdacytumn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sports-merch" /></template>
<style>
.wdacytumn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.931 8h10.138a2.625 2.625 0 0 1 2.617 2.424l.597 7.75A2.625 2.625 0 0 1 17.665 21H6.335a2.625 2.625 0 0 1-2.618-2.826l.597-7.75A2.625 2.625 0 0 1 6.931 8M8.5 8V6.5a3.5 3.5 0 0 1 7 0V8M4.25 11.5h15.5");
}

</style>
