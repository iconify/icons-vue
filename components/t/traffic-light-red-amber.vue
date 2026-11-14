<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ugukxwbqn"/><path class="x9yqeab1q"/><path class="j6nyvsbjt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:traffic-light-red-amber" /></template>
<style>
.j6nyvsbjt {
  d: path("M10.5 17.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ugukxwbqn {
  d: path("M8.75 2h6.5a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1h-6.5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x9yqeab1q {
  fill: currentColor;
  d: path("M10.5 6.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm0 5.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

</style>
