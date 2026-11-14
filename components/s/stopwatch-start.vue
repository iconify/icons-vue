<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cehb8pb0w"/><path class="o5l6hu9yr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stopwatch-start" /></template>
<style>
.cehb8pb0w {
  d: path("M4 13.25a8 8 0 1 0 16 0a8 8 0 1 0-16 0ZM12 2.5v2.75M10 2.5h4");
}

.o5l6hu9yr {
  d: path("m9.75 9.25l6.75 4l-6.75 4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
