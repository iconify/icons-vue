<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xgrfb-bqu"/><path class="d8abqfbpc"/><path class="k0js09kko"/><path class="xms4a9qrp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stop-reason-outline-regular" /></template>
<style>
.d8abqfbpc {
  d: path("M3 11h18");
}

.k0js09kko {
  d: path("M3 16h9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

.xms4a9qrp {
  d: path("M15 14h4v4h-4Z");
}

</style>
