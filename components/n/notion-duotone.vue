<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yk1-n-esz"/><path class="kj7y5ub8v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:notion-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kj7y5ub8v {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 17v-7l5 7v-7M3 3h15l3 3v15H6l-3-3Zm18 3H6v15M3 3l3 3");
}

.yk1-n-esz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 2h15c.265 0 .52.105.707.293l3 3A1 1 0 0 1 22 6v15a1 1 0 0 1-1 1H6a1 1 0 0 1-.707-.293l-3-3A1 1 0 0 1 2 18V3a1 1 0 0 1 1-1");
}

</style>
