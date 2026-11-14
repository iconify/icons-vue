<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o99aq0n5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-fish" /></template>
<style>
.o99aq0n5w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M21.5 12C19 7 15 5.5 11.5 6.5C9 7.25 7.25 9.25 6 12c1.25 2.75 3 4.75 5.5 5.5c3.5 1 7.5-.5 10-5.5ZM6 12L3 8l1 4l-1 4Zm10.5-1.5h.01");
}

</style>
