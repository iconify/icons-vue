<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k2c5x4bmu"/><path class="dkburmbco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ship-duocolor" /></template>
<style>
.dkburmbco {
  d: path("m4 17l-1-3l9-3l9 3l-1 3M6 13V8a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v5M12 3v3m0 5v6");
}

.k2c5x4bmu {
  stroke-opacity: 0.4;
  d: path("M2 20c.5.5 1 1 2 1c2 0 2-2 4-2s2 2 4 2s2-2 4-2s2 2 4 2c1 0 1.5-.5 2-1");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
