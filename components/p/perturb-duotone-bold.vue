<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uda6dfbwy"/><path class="rn81pnx9i"/><path class="ozi-k-boi"/><path class="ph2id7bdf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:perturb-duotone-bold" /></template>
<style>
.ozi-k-boi {
  d: path("M3 7h18");
}

.ph2id7bdf {
  d: path("m3 15 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

.rn81pnx9i {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 15 3 -3 3 3 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uda6dfbwy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 7h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
