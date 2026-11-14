<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x1gr0bbnb"/><path class="e_92r1bfh"/><path class="s7v73ac1b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:skin-cancer-check" /></template>
<style>
.e_92r1bfh {
  fill: currentColor;
  d: path("M8.25 8c1.25-.75 2.75 0 3 1.5s-1 2.5-2.25 2.25s-2-1.5-1.5-2.5Z");
}

.s7v73ac1b {
  d: path("m14.5 18l2.5 2.5l4.5-5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x1gr0bbnb {
  d: path("M2.5 16.5c2.5-1 4.5 1 7 0c1.003-.376 1.88-.312 2.694-.187M7.5 5.5c2-1.5 5-.75 6 1.5s-.25 4 .25 5.75c.25 1.5-1.75 2.25-3.5 1.5c-2 .75-4.5 0-5-2s.75-3.5.5-4.75c0-.75.75-1.5 1.75-2Z");
}

</style>
