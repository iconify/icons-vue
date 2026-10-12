<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agyzjndwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:page-break" /></template>
<style>
.agyzjndwy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 10V4.75a2 2 0 0 1 2-2h7l4.5 4.5V10m-4.5-7.25v4.5h4.5M5.25 14v5.25a2 2 0 0 0 2 2h9.5a2 2 0 0 0 2-2V14m-16-2h3m4.75 0h3m4.75 0h3");
}

</style>
