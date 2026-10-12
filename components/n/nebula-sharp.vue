<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="z4xvz7b3w"/><path class="t664s5_ea"/><path class="c9oiszudw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nebula-sharp" /></template>
<style>
.c9oiszudw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.5 3.5h.01");
}

.t664s5_ea {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8.5q.48 3.52 4 4q-3.52.48-4 4q-.48-3.52-4-4q3.52-.48 4-4Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.z4xvz7b3w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.09 9.82l.57-1.14L6 6l2.5-.62l2.5-.63l2 1.13L15 7l2.25.38l2.25.37l.88 2.63l.87 2.62l-1.64 2.51l-.47.73l-1.64 2.51l-2.97.46l-.56.08l-2.97.46l-2.79-1.09l-.17-.07l-2.79-1.09L4 15l-1.25-2.5z");
}

</style>
