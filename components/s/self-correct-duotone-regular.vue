<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q41_xjt0c"/><path class="o778d9blf"/><path class="v51ihtbid"/><path class="e10w3sbws"/><path class="hxs7cr7lm"/><path class="grpcwaciz"/><path class="fy72pvbym"/><path class="bwel3nf-y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:self-correct-duotone-regular" /></template>
<style>
.bwel3nf-y {
  d: path("m16 15 2 2 3 -3");
}

.e10w3sbws {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 15 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fy72pvbym {
  d: path("M4 16h10");
}

.grpcwaciz {
  d: path("m4 10 6 -6");
}

.hxs7cr7lm {
  d: path("M4 7h10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o778d9blf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m4 10 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q41_xjt0c {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 7h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v51ihtbid {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 16h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
