<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="iu27ft--w"/><path class="ntazt1bsz"/><path class="ivfkkwjwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wax-seal-sharp" /></template>
<style>
.iu27ft--w {
  d: path("M11.25 2.95c1.22.2 1.91.84 3.21 1.41s2.46.45 3.3 1.43c.85.98.58 2.08.93 3.47c.35 1.38.93 2.25.83 3.45s-1.07 1.5-1.34 2.54c-.28 1.04.06 1.8-.02 2.67l-.137 1.489l-.243.191l-.177.136l-1.553-.176c-.97-.1-1.88-.5-3.14-.48c-1.25.01-1.93.86-3.14.54c-1.2-.32-1.7-1.32-2.88-2.14c-1.18-.83-2.34-.87-3-1.98s-.2-2.15-.31-3.58c-.11-1.42-.68-2.33-.22-3.54s1.51-1.5 2.52-2.5c1-1.01 1.42-1.94 2.5-2.52l1.231-.679z");
}

.ivfkkwjwb {
  d: path("m12.6 9.5l-.45-.6h-2.3v1.05c0 1.5 2.8.9 2.8 2.45v1.1H10.3l-.45-.6");
}

.ntazt1bsz {
  d: path("M16 11.25a4.75 4.75 0 1 1-9.5 0a4.75 4.75 0 0 1 9.5 0");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
