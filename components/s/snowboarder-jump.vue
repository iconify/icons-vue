<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1sl2xbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:snowboarder-jump" /></template>
<style>
.g1sl2xbxf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5V19Q7 18 11 14.5v6Zm9.758-10.37l8.458-3.079l1.026 2.819l-8.458 3.079ZM4 13q3.5-7.5 9.5-7.5");
}

</style>
