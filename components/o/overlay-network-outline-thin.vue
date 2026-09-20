<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pmuiqo95v"/><path class="uxcq0c75d"/><path class="o5h857ycu"/><path class="vq8t-6zzl"/><path class="it83nbbll"/><path class="dxdpz6gbz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:overlay-network-outline-thin" /></template>
<style>
.dxdpz6gbz {
  d: path("M17 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.it83nbbll {
  d: path("M5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.o5h857ycu {
  d: path("M17 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.pmuiqo95v {
  d: path("M2 17h20");
}

.uxcq0c75d {
  d: path("M5 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.vq8t-6zzl {
  d: path("m6 12 6 -6 6 6");
}

</style>
