<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c6zbqlbwf"/><path class="oexizmbbx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ping-pong-serve" /></template>
<style>
.c6zbqlbwf {
  d: path("M10 12.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

.oexizmbbx {
  d: path("m10.404 14.975l2.121 2.121l-3.535 3.536l-2.122-2.122ZM3.75 5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM6 15V9.75M4.25 11.5L6 9.75l1.75 1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
