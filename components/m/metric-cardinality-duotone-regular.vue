<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="u-s2qjbyd"/><path class="iqnh9hbxr"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="wdvszqb6r"/><path class="l0kkv4bte"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:metric-cardinality-duotone-regular" /></template>
<style>
.iqnh9hbxr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 17 17 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iulb4mb6k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l0kkv4bte {
  d: path("M7 17 17 7");
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

.r3faxubne {
  d: path("M4 4v16");
}

.u-s2qjbyd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 5v12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wdvszqb6r {
  d: path("M7 5v12h12");
}

</style>
