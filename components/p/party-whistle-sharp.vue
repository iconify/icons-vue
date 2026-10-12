<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="k64s9jhhq"/><path class="p3mql2b-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:party-whistle-sharp" /></template>
<style>
.k64s9jhhq {
  d: path("M2.75 10.25h4.5v3.5h-4.5zm5.25.5h8v2.5H8z");
}

.p3mql2b-b {
  d: path("M16 12h2.25a3 3 0 0 1 0 6h-3v-3h2.25M9 6.25l1-1.5m3 1v-2m3.5 2.5l1-1.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
