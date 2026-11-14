<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hi_5hbt7a"/><path class="uuzhz2b0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:observation-car" /></template>
<style>
.hi_5hbt7a {
  d: path("M2.5 14.75v-5A1.5 1.5 0 0 1 4 8.25h3.5c1-4.25 8-4.25 9 0H20a1.5 1.5 0 0 1 1.5 1.5v5ZM5 11.5h2.75m2.75 0h3m2.75 0H19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uuzhz2b0m {
  d: path("M4.25 16.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm12 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM2.5 18.25h19");
}

</style>
