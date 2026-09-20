<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eff5yibna"/><path class="xs2k_0b3a"/><path class="engmigelj"/><path class="g7it-uy-z"/><path class="x240p6o1n"/><path class="iz6w2nite"/><path class="pq9ly31-r"/><path class="wgmj3x5ib"/><path class="h_yag6b0i"/><path class="zc1w0xe2t"/><path class="qv5w5objz"/><path class="c7u43zhgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pose-duotone-thin" /></template>
<style>
.c7u43zhgq {
  d: path("m12 14 5 5");
}

.eff5yibna {
  fill: currentColor;
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.engmigelj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 8 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g7it-uy-z {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 8 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h_yag6b0i {
  d: path("m12 8 -5 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iz6w2nite {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 14 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pq9ly31-r {
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.qv5w5objz {
  d: path("m12 14 -5 5");
}

.wgmj3x5ib {
  d: path("M12 6v8");
}

.x240p6o1n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 14 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xs2k_0b3a {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 6v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zc1w0xe2t {
  d: path("m12 8 5 5");
}

</style>
