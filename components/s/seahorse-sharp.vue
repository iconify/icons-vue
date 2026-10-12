<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="b3f1fxbjk"/><path class="uad4q5bpp"/><path class="c571tqvaq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:seahorse-sharp" /></template>
<style>
.b3f1fxbjk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3.5c1.5-.75 3.5-.5 4.75.75s1.5 3 .75 4.25c2.75.75 4.5 3 4.25 5.75c-.25 2.5-2 4.25-4.75 4.75l-1.25.25V15.5c0-1.75-1-3-2.5-4l-1-.667V9.5l-3.5 1.25l-2.625.875L5 9.75L8.5 6.5l-.417-2.083zm9.25 7l2-.5l1.563-.312L20.7 10.8l-1.8 1.8Z");
}

.c571tqvaq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.25 6.25h.01");
}

.uad4q5bpp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.5 19.25l-.4 2H9.5V18.5h1.25");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
