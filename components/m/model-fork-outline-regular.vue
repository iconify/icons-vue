<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qz_by4b2x"/><path class="gc9dmfy3u"/><path class="zzazs-rvi"/><path class="ll_i_4bra"/><path class="ud-rllqqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:model-fork-outline-regular" /></template>
<style>
.gc9dmfy3u {
  d: path("m10.5 7.5 -5 5");
}

.ll_i_4bra {
  d: path("M2.5 14.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qz_by4b2x {
  d: path("m12 4 2.5 2.5L12 9 9.5 6.5Z");
}

.ud-rllqqn {
  d: path("M17.5 14.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.zzazs-rvi {
  d: path("m13.5 7.5 5 5");
}

</style>
