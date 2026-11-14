<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="en-rl8o1b"/><path class="lm8l13b6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sleeping-bag-liner" /></template>
<style>
.en-rl8o1b {
  d: path("M12 2.5c4 0 5.5 2.5 5.5 5.5c0 5-1.5 9-2.5 13.5H9C8 17 6.5 13 6.5 8C6.5 5 8 2.5 12 2.5Z");
}

.lm8l13b6j {
  d: path("M9.5 7a2.5 2 0 1 0 5 0a2.5 2 0 1 0-5 0Zm0 4.75c0 2.75 1 5.25 1.75 7h1.5c.75-1.75 1.75-4.25 1.75-7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
