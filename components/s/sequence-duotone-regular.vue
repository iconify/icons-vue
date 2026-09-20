<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zxrob3sge"/><path class="dktry7bqc"/><path class="cpc3z_b1u"/><path class="witzjrb2w"/><path class="tctgr7j5z"/><path class="dfcdzc65k"/><path class="orctd05jx"/><path class="bo51iypxr"/><path class="rija-f-oa"/><path class="kdmnrabtq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sequence-duotone-regular" /></template>
<style>
.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.cpc3z_b1u {
  fill: currentColor;
  d: path("M17 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.dfcdzc65k {
  d: path("M3 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.dktry7bqc {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.kdmnrabtq {
  d: path("M17 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.orctd05jx {
  d: path("m7.5 7.5 2 2");
}

.rija-f-oa {
  d: path("m14.5 14.5 2 2");
}

.tctgr7j5z {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m14.5 14.5 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.witzjrb2w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7.5 7.5 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zxrob3sge {
  fill: currentColor;
  d: path("M3 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
