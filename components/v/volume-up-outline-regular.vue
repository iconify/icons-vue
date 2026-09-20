<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wgofw5b0q"/><path class="egkr7d65p"/><path class="nhqzfzb7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:volume-up-outline-regular" /></template>
<style>
.egkr7d65p {
  d: path("M17 8.54a4 4 0 0 1 0 6.92");
}

.nhqzfzb7u {
  d: path("M18.5 5.94a7 7 0 0 1 0 12.12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wgofw5b0q {
  d: path("M3 9h5l5 -5v16l-5 -5H3Z");
}

</style>
