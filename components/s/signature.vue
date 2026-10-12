<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsxlr7ghc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:signature" /></template>
<style>
.hsxlr7ghc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 15.75c2-4.5 4.25-9 5.75-8c2 1.25-3.5 8-1.25 8.25c1.75.25 3-3.75 4.75-3.75c1.25 0 .5 2.5 2 2.5s2.5-2.25 4.5-2.25M3.75 20.25h16.5");
}

</style>
