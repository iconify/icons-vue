<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lqcp5xb1v"/><path class="t3vzob-fn"/><path class="mzkwo-z2x"/><path class="v3qgglbcl"/><path class="phup74asp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:request-timeline-outline-regular" /></template>
<style>
.lqcp5xb1v {
  d: path("M4 3h16");
}

.mzkwo-z2x {
  d: path("M7 9.5v5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.phup74asp {
  d: path("M17 9.5v5");
}

.t3vzob-fn {
  d: path("M2 12a6 6 0 0 1 6 -6h8a6 6 0 0 1 6 6 6 6 0 0 1 -6 6H8a6 6 0 0 1 -6 -6");
}

.v3qgglbcl {
  d: path("M12 9.5v5");
}

</style>
