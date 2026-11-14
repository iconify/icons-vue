<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ghtz8h6wm"/><path class="j5u8lsqcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:replay-30" /></template>
<style>
.ghtz8h6wm {
  d: path("M12 5.5a7.5 7.5 0 1 1-6.495 3.75");
}

.j5u8lsqcb {
  d: path("m15 2.5l-3 3l3 3m-7.5 2h3l-1.5 2m0 0c1.25 0 1.75.75 1.75 1.5c0 1-.75 1.5-1.5 1.5q-1.125 0-1.5-.75m5.5-4.25h3v5h-3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
