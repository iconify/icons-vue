<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a5cnt_bku"/><path class="mg6i_wlie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-food-bag" /></template>
<style>
.a5cnt_bku {
  d: path("m5.5 7l-1 12.5A1.5 1.5 0 0 0 6 21h12a1.5 1.5 0 0 0 1.5-1.5L18.5 7m-14-3.5h15V7h-15Z");
}

.mg6i_wlie {
  d: path("M9.5 12.75h5A1.25 1.25 0 1 1 15.75 14a1.25 1.25 0 1 1-1.25 1.25h-5A1.25 1.25 0 1 1 8.25 14a1.25 1.25 0 1 1 1.25-1.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
