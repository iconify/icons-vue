<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dc7s40ben"/><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="t5n_tik8k"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="zvg9k5fuv"/><path class="nz5g1fb0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:metric-drilldown-duotone-regular" /></template>
<style>
.dc7s40ben {
  fill: currentColor;
  d: path("M9 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.iulb4mb6k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nz5g1fb0o {
  d: path("M11.5 10.5 15 14");
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

.t5n_tik8k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11.5 10.5 15 14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zvg9k5fuv {
  d: path("M9 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
