<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mjxjq9e4f"/><path class="bzecsub_a"/><path class="y_or9-s0p"/><path class="oeboj9bgs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:test-select-outline-regular" /></template>
<style>
.bzecsub_a {
  d: path("M8 12h12");
}

.mjxjq9e4f {
  d: path("M8 5h12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oeboj9bgs {
  d: path("m3 9 3 3 -3 3Z");
}

.y_or9-s0p {
  d: path("M8 19h12");
}

</style>
