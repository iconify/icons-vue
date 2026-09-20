<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k6nj2fbya"/><path class="nvu1cl7xd"/><path class="h6d75qzkp"/><path class="ln075ccaf"/><path class="awx6ohc-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sla-freshness-outline-regular" /></template>
<style>
.awx6ohc-u {
  d: path("M16 15h3");
}

.h6d75qzkp {
  d: path("M11.5 15a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.ln075ccaf {
  d: path("M16 12v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nvu1cl7xd {
  d: path("M3 10h9");
}

</style>
