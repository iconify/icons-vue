<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="unfms0bro"/><path class="hy_n6wb9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-music-venue" /></template>
<style>
.hy_n6wb9f {
  d: path("M5.5 10.5a6.5 6.5 0 0 0 13 0M12 17v4m-3.5 0h7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.unfms0bro {
  d: path("M10 2.5h4A1.5 1.5 0 0 1 15.5 4v8a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 8.5 12V4A1.5 1.5 0 0 1 10 2.5Z");
}

</style>
