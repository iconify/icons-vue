<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="notsg96wk"/><path class="tzl6tonde"/><path class="rdlxynb9x"/><path class="lbkuffism"/><path class="wt9iv5biz"/><path class="olx65-bog"/><path class="exyd3ub4k"/><path class="oqfv9rb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ski-trip-duotone-regular" /></template>
<style>
.exyd3ub4k {
  d: path("m9 8 6 -6");
}

.lbkuffism {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 21h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.notsg96wk {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m2 19 6 -6 3 3 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.olx65-bog {
  d: path("m6 8 6 -6");
}

.oqfv9rb9x {
  d: path("M2 21h20");
}

.rdlxynb9x {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 8 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tzl6tonde {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6 8 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wt9iv5biz {
  d: path("m2 19 6 -6 3 3 5 -5 5 5");
}

</style>
