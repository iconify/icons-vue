<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vowqhkvry"/><path class="hd8b2vurz"/><path class="wmzuyfbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:specimen-fridge" /></template>
<style>
.hd8b2vurz {
  d: path("M12.75 11v5.25c0 .85.65 1.5 1.5 1.5s1.5-.65 1.5-1.5V11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vowqhkvry {
  d: path("M5.5 2.5h13V20h-13Zm0 6h13M8 4.5v2M8 11v3.5M7.75 20v1.5m8.5-1.5v1.5");
}

.wmzuyfbzj {
  fill: currentColor;
  d: path("M12.75 14.25h3v2c0 .85-.65 1.5-1.5 1.5s-1.5-.65-1.5-1.5Z");
}

</style>
