<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dppbyqydk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vr-screenshot" /></template>
<style>
.dppbyqydk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 8.5h7a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2H14L12.75 14h-1.5L10 15.5H8.5a2 2 0 0 1-2-2v-3a2 2 0 0 1 2-2ZM2.5 7V2.5H7m10 0h4.5V7m0 10v4.5H17m-10 0H2.5V17");
}

</style>
