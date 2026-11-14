<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="awctw-b7r"/><path class="e2jaasbfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wheelchair-push" /></template>
<style>
.awctw-b7r {
  d: path("M3.5 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2 3.5l.5 6l-1.5 6.5M6 14l2 6.5m-2.25-11H11M11 8l1.5 6.5H19l1.5 4.5");
}

.e2jaasbfm {
  d: path("M12 17.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
