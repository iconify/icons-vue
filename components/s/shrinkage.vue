<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dircu6b5e"/><path class="j8mwjdp0l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shrinkage" /></template>
<style>
.dircu6b5e {
  d: path("M16.5 4.75L12 2.5L3 7v10l9 4.5l9-4.5v-4.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j8mwjdp0l {
  d: path("M16.5 4.75v4.5l4.5 3M3 7l9 4.5l4.5-2.25M12 11.5v10m6-16l1.5.75M21 8.5V10");
}

</style>
