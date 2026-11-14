<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i2ezp6v1p"/><path class="unz-u2b8g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:round-up-donation" /></template>
<style>
.i2ezp6v1p {
  d: path("M13.009 20.423L12 21l-3.5-2L5 21V3h14v9.5m-10.5-5h7m-7 3.5h7m-7 3.5h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.unz-u2b8g {
  d: path("m18 21.5l-2.75-2.75c-1-1-.75-3.5 1-3.5c1 0 1.5.75 1.75 1.25c.25-.5.75-1.25 1.75-1.25c1.75 0 2 2.5 1 3.5Z");
}

</style>
