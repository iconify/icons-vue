<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fomq-_kfd"/><path class="um6p14byg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-droplet-duotone" /></template>
<style>
.fomq-_kfd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 3h14a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2m7 5s-3.111 2.222-3.111 4.889a3.111 3.111 0 0 0 6.222 0C15.111 10.222 12 8 12 8");
}

.ft5dv1b6b {
  fill: none;
}

.um6p14byg {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm9 3s-3.111 2.222-3.111 4.889a3.111 3.111 0 1 0 6.222 0C15.111 10.222 12 8 12 8");
}

</style>
