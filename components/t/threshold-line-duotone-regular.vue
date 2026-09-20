<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="ef4b-rb-i"/><path class="w4x83gbcm"/><path class="w3hnpdk3b"/><path class="frc90pbsi"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="e_6o-gbms"/><path class="a5uqb5btg"/><path class="qn21uclav"/><path class="mcdduacou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:threshold-line-duotone-regular" /></template>
<style>
.a5uqb5btg {
  d: path("M9 14v4");
}

.e_6o-gbms {
  d: path("M6 10h13");
}

.ef4b-rb-i {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 10h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.frc90pbsi {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 7v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iulb4mb6k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mcdduacou {
  d: path("M17 7v11");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.pd-i35blz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qn21uclav {
  d: path("M13 12v6");
}

.r3faxubne {
  d: path("M4 4v16");
}

.w3hnpdk3b {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 12v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w4x83gbcm {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
