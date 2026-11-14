<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="px3_0obhn"/><path class="ihckwjb_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:news-feed-x" /></template>
<style>
.ihckwjb_o {
  d: path("M6 9.75h5.5v5.5H6Zm8.25.5H17m-1.5 5.25l5 5m0-5l-5 5");
}

.px3_0obhn {
  d: path("M11.6 20.5H2.5v-18h18v9.1M6 6.5h11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
