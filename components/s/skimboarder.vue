<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a9_ydt7uv"/><path class="bkt517b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:skimboarder" /></template>
<style>
.a9_ydt7uv {
  d: path("M10 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-6.5 5h17");
}

.bkt517b4s {
  d: path("M12 6.5V14l-4 5.5m4-5.5l4 5.5m-13 0h18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
