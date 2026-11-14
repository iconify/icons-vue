<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anhvwbn2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:nas-box" /></template>
<style>
.anhvwbn2g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h14v16h-14ZM6 9h4m-4 5h4m3-5h.01M13 14h.01m3.49-2h2a2.5 2.5 0 0 1 2.5 2.5v6");
}

</style>
