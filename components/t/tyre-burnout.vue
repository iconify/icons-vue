<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t55d_qb_x"/><path class="yzduaxcrw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tyre-burnout" /></template>
<style>
.t55d_qb_x {
  d: path("M8.75 10a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yzduaxcrw {
  d: path("M12 10a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Zm-2 11H6a2 2 0 1 1 2-2m-1.25-5h-2.5a2 2 0 1 1 2-2");
}

</style>
