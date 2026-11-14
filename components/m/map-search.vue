<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p3qbjccuu"/><path class="v71hr-b5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:map-search" /></template>
<style>
.p3qbjccuu {
  d: path("m3 6l6-2.5L15 6l6-2.5v8.75h-8.75v7L9 18l-6 2.5Zm6-2.5V18m6-12v6.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v71hr-b5u {
  d: path("M15 17.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM19 19l1.75 1.75");
}

</style>
