<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n1dh62bby"/><path class="sz6a4q08e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:traffic-radar" /></template>
<style>
.n1dh62bby {
  d: path("M3.5 7H13V5.5h2.5v9H13v-2H3.5a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1Z");
}

.sz6a4q08e {
  d: path("M5.5 12.5L4 20h3.25L9 12.5m9.25-5a4 4 0 0 1 0 5m2-7a7 7 0 0 1 0 9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
