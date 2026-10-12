<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="chc1rqbnv"/><path class="tvtpt-ghx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:office-location" /></template>
<style>
.chc1rqbnv {
  d: path("M12 21.25c-.35 0-.7-.13-.95-.38C8.1 18.1 4.75 14.4 4.75 10a7.25 7.25 0 0 1 14.5 0c0 4.4-3.35 8.1-6.3 10.87c-.25.25-.6.38-.95.38");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tvtpt-ghx {
  d: path("M9.25 9.75h5.5a.75.75 0 0 1 .75.75V13a.75.75 0 0 1-.75.75h-5.5A.75.75 0 0 1 8.5 13v-2.5a.75.75 0 0 1 .75-.75m1.25 0v-2.5h3v2.5");
}

</style>
