<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7jcxcbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:steam-room-hotel" /></template>
<style>
.g7jcxcbtp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14.5h19V18h-19Zm3 3.5v3m13-3v3M7 11.5C5.5 10 8.5 8 7 6.5s1.5-3 0-4m5 9c-1.5-1.5 1.5-3.5 0-5s1.5-3 0-4m5 9c-1.5-1.5 1.5-3.5 0-5s1.5-3 0-4");
}

</style>
