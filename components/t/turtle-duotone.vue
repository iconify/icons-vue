<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o2irrtb8u"/><path class="o59eu7_zd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:turtle-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.o2irrtb8u {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16.247 9H19a3 3 0 1 1 0 6h-1v2a2 2 0 0 1-2 2h-1a2 2 0 0 1-2-2v-2H7v2a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2v-3a8 8 0 0 1 14.247-5");
}

.o59eu7_zd {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 14a7 7 0 0 1 14 0Zm12.745-4H19a2 2 0 1 1 0 4h-2a7 7 0 0 0-1.255-4M8 11h4m-4 0L6.476 7.952M12 11l1.524-3.048M3 14v3a1 1 0 0 0 1 1h1a1 1 0 0 0 1-1v-3m8 0v3a1 1 0 0 0 1 1h1a1 1 0 0 0 1-1v-3");
}

</style>
