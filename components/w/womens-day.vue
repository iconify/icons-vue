<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rl5u5dboy"/><path class="xf5sxpban"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:womens-day" /></template>
<style>
.rl5u5dboy {
  d: path("M5.5 9a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Zm6.5 6.5v6m-3-3h6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xf5sxpban {
  d: path("M12 11.5S9.5 10 9.5 8.25c0-.75.6-1.25 1.25-1.25c.5 0 .95.3 1.25.75c.3-.45.75-.75 1.25-.75c.65 0 1.25.5 1.25 1.25C14.5 10 12 11.5 12 11.5Z");
}

</style>
