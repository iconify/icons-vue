<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m3ni4eojn"/><path class="b6a_6hp0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:reading-aloud" /></template>
<style>
.b6a_6hp0d {
  d: path("M19.277 5.894a9.5 9.5 0 0 1 0 12.212");
}

.m3ni4eojn {
  d: path("M12 6.5c-2-1.5-4.75-2-9.5-2V18c4.75 0 7.5.5 9.5 2c2-1.5 4.75-2 9.5-2V4.5c-4.75 0-7.5.5-9.5 2Zm0 0V20");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
