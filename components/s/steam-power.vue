<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1l9-pb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:steam-power" /></template>
<style>
.x1l9-pb6x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10h13v11.5h-13ZM9 15.75h12.5M9 10v11.5M6 7.25C4.5 5.75 7.5 4 6 2.5m6 4.75C10.5 5.75 13.5 4 12 2.5");
}

</style>
