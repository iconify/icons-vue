<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="z37w-kbgi"/><path class="qb2c6s8kx"/><path class="kx87wwb-h"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="x3ookvx2e"/><path class="kuui-zbsa"/><path class="c08_j9b_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:staleness-marker-duotone-regular" /></template>
<style>
.c08_j9b_a {
  d: path("m19.5 11.5 -3 3");
}

.iulb4mb6k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kuui-zbsa {
  d: path("m16.5 11.5 3 3");
}

.kx87wwb-h {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m19.5 11.5 -3 3");
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

.qb2c6s8kx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16.5 11.5 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.x3ookvx2e {
  d: path("m7 17 4 -4h3");
}

.z37w-kbgi {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7 17 4 -4h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
