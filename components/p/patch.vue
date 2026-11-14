<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yac4tubqo"/><path class="mr8jfwb3f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:patch" /></template>
<style>
.mr8jfwb3f {
  d: path("M7.757 12L12 7.757L16.243 12L12 16.243ZM11 11h.01M13 13h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yac4tubqo {
  d: path("M4.222 15.536L15.536 4.222a1 1 0 0 1 1.414 0l2.828 2.828a1 1 0 0 1 0 1.414L8.464 19.778a1 1 0 0 1-1.414 0L4.222 16.95a1 1 0 0 1 0-1.414Z");
}

</style>
