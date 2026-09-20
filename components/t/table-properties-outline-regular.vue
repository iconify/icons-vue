<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n48w5yb-p"/><path class="t87ohzbeq"/><path class="w9es-hz-w"/><path class="pfakvcc9e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:table-properties-outline-regular" /></template>
<style>
.n48w5yb-p {
  d: path("M14 4h5a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pfakvcc9e {
  d: path("M9 15h13");
}

.t87ohzbeq {
  d: path("M9 4v16");
}

.w9es-hz-w {
  d: path("M9 9h13");
}

</style>
