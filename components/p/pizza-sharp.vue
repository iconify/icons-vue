<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="k1vlxhbrt"/><path class="x1buefbkz"/><path class="t5fogdb9i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pizza-sharp" /></template>
<style>
.k1vlxhbrt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 6.5c5.5-3.25 12-3.25 17.5 0L12.9 20.7l-.9 1.858l-.9-1.858Z");
}

.t5fogdb9i {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 12.25h.01m4.49-.5h.01M12 16h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.x1buefbkz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 9.25C9.25 7 14.75 7 19 9.25");
}

</style>
