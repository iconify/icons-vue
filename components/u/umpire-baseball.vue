<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="id67wccqw"/><path class="unr8p9i_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:umpire-baseball" /></template>
<style>
.id67wccqw {
  d: path("M9 2.5h6a2 2 0 0 1 2 2V11a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2V4.5a2 2 0 0 1 2-2Zm-5 19c0-3 3.5-5.5 8-5.5s8 2.5 8 5.5M7 7h10m-6.5 0v6m3-6v6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.unr8p9i_x {
  d: path("M8.5 16.75v1.75a3.5 3 0 0 0 7 0v-1.75");
}

</style>
