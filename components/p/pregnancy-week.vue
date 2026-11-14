<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psmddu2uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pregnancy-week" /></template>
<style>
.psmddu2uv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.717 17.992A4.4 4.4 0 0 1 10.5 18l-.25 3.5H5V17c-.75-1.5-1.25-4-1-6c.25-1.5.75-2.5 1.5-2.5h3c1 0 1.5.5 1.75 1.5l.25 1c1.087.326 1.985.841 2.632 1.484M5.25 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm9.25 10.5h7v6.5h-7Zm0 2.5h7m-5-3.75v1.5m3-1.5v1.5");
}

</style>
