<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="c9b9cdc0r"/><path class="z_86k9bdq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shapes-duotone" /></template>
<style>
.c9b9cdc0r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11.796 7.891A2 2 0 0 1 10.131 11H5.869a2 2 0 0 1-1.665-3.109l2.132-3.198a2 2 0 0 1 3.328 0Zm.597 7.162a5.001 5.001 0 1 1 9.213 3.896a5.001 5.001 0 0 1-9.213-3.896M4 14h4a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2");
}

.ft5dv1b6b {
  fill: none;
}

.z_86k9bdq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 16a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Zm10 1a4 4 0 1 0 8 0a4 4 0 0 0-8 0M8.832 5.248l2.132 3.197A1 1 0 0 1 10.13 10H5.87a1 1 0 0 1-.833-1.555l2.132-3.197a1 1 0 0 1 1.664 0");
}

</style>
