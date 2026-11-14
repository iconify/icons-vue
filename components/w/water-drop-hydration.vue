<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yu8pi5bvl"/><path class="k7r9h1f1n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:water-drop-hydration" /></template>
<style>
.k7r9h1f1n {
  d: path("M12 11.25c1.25 1.5 2.25 2.5 2.25 4c0 1.25-1 2.25-2.25 2.25s-2.25-1-2.25-2.25c0-1.5 1-2.5 2.25-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yu8pi5bvl {
  d: path("M6.5 8h11v13.5h-11Zm2-3h7v3h-7Zm2 0V2.75H13");
}

</style>
