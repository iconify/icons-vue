<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="li36wh32f"/><path class="y37ojabar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:microwave-smart" /></template>
<style>
.li36wh32f {
  d: path("M11.6 16H2.5V4.5h17v8.3m-5-8.3v9.4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y37ojabar {
  d: path("M5.25 7.25h6.5v6h-6.5ZM18.5 21.5h.01m-2.01-2.25a3 3 0 0 1 4 0m-5.25-2.5a5.5 5.5 0 0 1 6.5 0");
}

</style>
