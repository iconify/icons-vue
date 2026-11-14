<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tdb6cwbyh"/><path class="ol7_s_biz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:swipe-to-play" /></template>
<style>
.ol7_s_biz {
  d: path("M8.75 9L13 12.25L8.75 15.5Zm6.75 9.5h6M19 16l2.5 2.5L19 21");
}

.tdb6cwbyh {
  d: path("M12.7 20.5H4.5v-18H16v12.6M9 5.5h2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
