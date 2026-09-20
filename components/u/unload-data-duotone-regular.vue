<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y-yc7jgvt"/><path class="fagsaxb1p"/><path class="l517yxbln"/><path class="xtvmpefkx"/><path class="k43ew0kyq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:unload-data-duotone-regular" /></template>
<style>
.fagsaxb1p {
  d: path("M3 3v5h18V3");
}

.k43ew0kyq {
  d: path("M6 17a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.l517yxbln {
  d: path("M12 9v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xtvmpefkx {
  d: path("m8 13 4 -4 4 4");
}

.y-yc7jgvt {
  fill: currentColor;
  d: path("M6 17a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
