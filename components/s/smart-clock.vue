<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lpbm8vbfk"/><path class="lkua-1lrf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smart-clock" /></template>
<style>
.lkua-1lrf {
  d: path("M12 10.25v3.25h3");
}

.lpbm8vbfk {
  d: path("M5 13.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0ZM3 8a3.75 3.75 0 0 1 5-5Zm13-5a3.75 3.75 0 0 1 5 5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
