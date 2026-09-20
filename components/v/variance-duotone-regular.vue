<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="ug-yr5rhi"/><path class="pk1epacxf"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="bw_to0b8d"/><path class="him6j9cua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:variance-duotone-regular" /></template>
<style>
.bw_to0b8d {
  d: path("M7 12h12");
}

.him6j9cua {
  d: path("M7 17 19 5");
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

.oifr9zbpt {
  d: path("M4 20h16");
}

.pd-i35blz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pk1epacxf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 17 19 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.ug-yr5rhi {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
