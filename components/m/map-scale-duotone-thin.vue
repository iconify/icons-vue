<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yf_brbf0s"/><path class="srrwlob2l"/><path class="vnzngacab"/><path class="cpiyi4b5g"/><path class="fkewqabpv"/><path class="d8abqfbpc"/><path class="h_c4fk0bb"/><path class="l3hfq7bhw"/><path class="gjmq94baq"/><path class="lfyekl_xx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:map-scale-duotone-thin" /></template>
<style>
.cpiyi4b5g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 11v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d8abqfbpc {
  d: path("M3 11h18");
}

.fkewqabpv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gjmq94baq {
  d: path("M15 11v4");
}

.h_c4fk0bb {
  d: path("M3 11v6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l3hfq7bhw {
  d: path("M9 11v4");
}

.lfyekl_xx {
  d: path("M21 11v6");
}

.srrwlob2l {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vnzngacab {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 11v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yf_brbf0s {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 11h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
