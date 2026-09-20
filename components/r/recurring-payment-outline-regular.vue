<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vyks9vbfn"/><path class="ogtwkzbca"/><path class="x-fetmmzo"/><path class="yqike0hdz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:recurring-payment-outline-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ogtwkzbca {
  d: path("M22 9.5h-7v5h7");
}

.vyks9vbfn {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.x-fetmmzo {
  d: path("M5 9.5 7.5 12 5 14.5");
}

.yqike0hdz {
  d: path("m9 9.5 2.5 2.5L9 14.5");
}

</style>
