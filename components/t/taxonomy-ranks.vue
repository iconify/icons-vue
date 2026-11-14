<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mwxxzhx5d"/><path class="wy-fvccem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:taxonomy-ranks" /></template>
<style>
.mwxxzhx5d {
  d: path("M9 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM2.5 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm13 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wy-fvccem {
  d: path("M12 8.5v4M5.5 15v-2.5h13V15");
}

</style>
