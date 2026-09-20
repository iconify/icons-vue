<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w18s0ubfz"/><path class="snqsppb6q"/><path class="t26juntbi"/><path class="caa4-_bka"/><path class="ibfqu4gsm"/><path class="kamdbib6v"/><path class="pmuiqo95v"/><path class="kt4_ogrrr"/><path class="hgjyjobhk"/><path class="gvpticbjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:waist-measure-duotone-regular" /></template>
<style>
.caa4-_bka {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 7v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gvpticbjc {
  d: path("M18 7v4");
}

.hgjyjobhk {
  d: path("M12 7v4");
}

.ibfqu4gsm {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 7v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kamdbib6v {
  d: path("M2 7h20");
}

.kt4_ogrrr {
  d: path("M6 7v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pmuiqo95v {
  d: path("M2 17h20");
}

.snqsppb6q {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 17h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t26juntbi {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 7v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w18s0ubfz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 7h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
