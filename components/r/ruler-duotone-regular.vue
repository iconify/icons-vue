<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r8dzomb3z"/><path class="qvq8nib-l"/><path class="p4maaes8e"/><path class="gte-olbep"/><path class="jz3tcofhe"/><path class="ktxx-etqf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ruler-duotone-regular" /></template>
<style>
.gte-olbep {
  d: path("M10 8v3.5");
}

.jz3tcofhe {
  d: path("M14 8v3.5");
}

.ktxx-etqf {
  d: path("M18 8v3.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p4maaes8e {
  d: path("M6 8v3.5");
}

.qvq8nib-l {
  d: path("M2 12a4 4 0 0 1 4 -4h12a4 4 0 0 1 4 4 4 4 0 0 1 -4 4H6a4 4 0 0 1 -4 -4");
}

.r8dzomb3z {
  fill: currentColor;
  d: path("M2 12a4 4 0 0 1 4 -4h12a4 4 0 0 1 4 4 4 4 0 0 1 -4 4H6a4 4 0 0 1 -4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
