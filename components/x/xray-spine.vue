<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tgx030-6f"/><path class="luf42usuo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:xray-spine" /></template>
<style>
.luf42usuo {
  d: path("M8.75 6L10 5.25h4l1.25.75m-6.5 3.25L10 8.5h4l1.25.75m-6.5 3.25l1.25-.75h4l1.25.75m-6.5 3.25L10 15h4l1.25.75M8.75 19l1.25-.75h4l1.25.75");
}

.tgx030-6f {
  d: path("M3 2.5h18v19H3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
