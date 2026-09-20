<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p68ditb-x"/><path class="s3elztrvy"/><path class="gcyir0cbn"/><path class="qbme7ibis"/><path class="arrljibna"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sponge-duotone-thin" /></template>
<style>
.arrljibna {
  d: path("M14 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.gcyir0cbn {
  d: path("M4 10a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p68ditb-x {
  fill: currentColor;
  d: path("M4 10a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qbme7ibis {
  d: path("M4 12c2 -2 4 2 6 0s4 2 6 0 3 1 4 0");
}

.s3elztrvy {
  fill: currentColor;
  d: path("M14 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
