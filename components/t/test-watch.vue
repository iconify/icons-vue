<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="umf6o6u3u"/><path class="hol9pewyh"/><path class="rn6jsgbjf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:test-watch" /></template>
<style>
.hol9pewyh {
  d: path("M6 10c1.5-2.5 3.5-3.5 6-3.5s4.5 1 6 3.5c-1.5 2.5-3.5 3.5-6 3.5s-4.5-1-6-3.5Z");
}

.rn6jsgbjf {
  fill: currentColor;
  d: path("M10.5 10a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.umf6o6u3u {
  d: path("M2.5 3h19v14h-19ZM12 17v4m-3.5 0h7");
}

</style>
