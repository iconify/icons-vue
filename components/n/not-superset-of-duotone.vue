<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="mh517eb7p"/><path class="c29fi2xlc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:not-superset-of-duotone" /></template>
<style>
.c29fi2xlc {
  d: path("M208 192H80.63l21.82-24H152a64 64 0 0 0 47.54-106.8l14.38-15.82a8 8 0 0 0-11.84-10.76l-14.65 16.11A63.66 63.66 0 0 0 152 40H56a8 8 0 0 0 0 16h96a47.7 47.7 0 0 1 24.51 6.75L95.37 152H56a8 8 0 0 0 0 16h24.82l-38.74 42.62a8 8 0 1 0 11.84 10.76L66.08 208H208a8 8 0 0 0 0-16M188.71 73.12A48 48 0 0 1 152 152h-35Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.mh517eb7p {
  d: path("M208 104a56 56 0 0 1-56 56H56V48h96a56 56 0 0 1 56 56");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
