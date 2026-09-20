<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r9kutnf3b"/><path class="ttx6bbv4v"/><path class="ts5r08i7u"/><path class="vdzoqccgg"/><path class="baci-hp8s"/><path class="ja-d7-b4a"/><path class="ic_pehd5a"/><path class="gyu499fcn"/><path class="k4y331wag"/><path class="xdvtlk8qz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:market-open-duotone-thin" /></template>
<style>
.baci-hp8s {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m19.5 9.5 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gyu499fcn {
  d: path("M12 6v2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ic_pehd5a {
  d: path("M3 17h18");
}

.ja-d7-b4a {
  d: path("M6 17a6 6 0 0 1 12 0");
}

.k4y331wag {
  d: path("m4.5 9.5 2 2");
}

.r9kutnf3b {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 17a6 6 0 0 1 12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ts5r08i7u {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 6v2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ttx6bbv4v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 17h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vdzoqccgg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4.5 9.5 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xdvtlk8qz {
  d: path("m19.5 9.5 -2 2");
}

</style>
