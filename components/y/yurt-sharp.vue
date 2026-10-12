<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="skccjx78g"/><path class="odom-c71q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:yurt-sharp" /></template>
<style>
.odom-c71q {
  d: path("M10.5 21.25v-4.5h3v4.5");
}

.skccjx78g {
  d: path("M2.75 13.25C5.5 10 8.5 7.5 12 6.25c3.5 1.25 6.5 3.75 9.25 7Zm9.25-7V3M3.75 13.25h16.5v8H3.75zm0 2.75H8.5m7 0h4.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
