<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1id9ib4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-games" /></template>
<style>
.o1id9ib4c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 6.5h10a4.75 4.75 0 0 1 4.5 6l-1 4.75a2.5 2.5 0 0 1-4 1.25l-2-2h-5l-2 2a2.5 2.5 0 0 1-4-1.25l-1-4.75a4.75 4.75 0 0 1 4.5-6Zm-1.25 5h4m-2-2v4M15.5 10h.01m2.24 2.75h.01");
}

</style>
