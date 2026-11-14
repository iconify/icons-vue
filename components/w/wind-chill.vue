<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4hb8jbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wind-chill" /></template>
<style>
.v4hb8jbao {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 13.5V5a2.5 2.5 0 0 1 5 0v8.5a4 4 0 1 1-5 0Zm9.5 3h4a1.5 1.5 0 1 0-1.5-1.5M15 19h5a1.5 1.5 0 1 1-1.5 1.5");
}

</style>
