<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bw7ptevmm"/><path class="n9jsisbkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:swimming-duotone-round" /></template>
<style>
.bw7ptevmm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 8a1 1 0 1 1 2 0a1 1 0 0 1-2 0");
}

.ft5dv1b6b {
  fill: none;
}

.n9jsisbkw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m5 11l5-3l4 3l-2 2m-9 4q3-3 6 0t6 0t6 0m-4-9a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
