<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wx106lesi"/><path class="myosl8bpc"/><path class="krcx7fb8u"/><path class="d_va93eda"/><path class="zuuudpbwi"/><path class="dzvfone4k"/><path class="k134iabcj"/><path class="cks97xg-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:throughput-duotone-regular" /></template>
<style>
.cks97xg-s {
  d: path("m14 13 3 3 -3 3");
}

.d_va93eda {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m14 13 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dzvfone4k {
  d: path("m14 5 3 3 -3 3");
}

.k134iabcj {
  d: path("M3 16h14");
}

.krcx7fb8u {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.myosl8bpc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m14 5 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wx106lesi {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 8h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zuuudpbwi {
  d: path("M3 8h14");
}

</style>
