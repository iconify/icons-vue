<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="o5ncru56h"/><path class="to8m3ibcr"/><path class="ndv572blb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:quasar-sharp" /></template>
<style>
.ndv572blb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75V6m0 12v3.25");
}

.o5ncru56h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12a9.25 3 0 1 0 18.5 0a9.25 3 0 1 0-18.5 0");
}

.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
