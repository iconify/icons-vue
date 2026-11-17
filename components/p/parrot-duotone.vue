<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dq1_89cyh"/><path class="sryocgbkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:parrot-duotone" /></template>
<style>
.dq1_89cyh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 5a5.07 5.07 0 0 1 4-2c2.5 0 4 2 4 5v3c0 2 1 4 2 6l3 4c-2.05-.513-3.95-1.487-6-2c-1.537-.205-3.022-.73-4-2c-1-1.5-2-3.5-2-5l-1-1c-1-1-2-1-2 0c-.001.503-.497.999-1 1c-1-.5-2-2-2-4s2-3 5-3");
}

.ft5dv1b6b {
  fill: none;
}

.sryocgbkw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 5c1-1.3 2.5-2 4-2c2.5 0 4 2 4 5v3c0 2 1 4 2 6l3 4c-2-.5-4-1.5-6-2c-1.5-.2-3-.7-4-2c-1-1.5-2-3.5-2-5l-1-1m-2 8h5m0-2v2m1-12h.01M8 5C5 5 3 6 3 8s1 3.5 2 4c.5 0 1-.5 1-1c0-1 1-1 2 0q.75-3 0-6");
}

</style>
