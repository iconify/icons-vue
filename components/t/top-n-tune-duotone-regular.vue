<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tokey8blw"/><path class="salcojbrw"/><path class="lkr_6zbxq"/><path class="hnd7f4g6i"/><path class="zn_kjwlsb"/><path class="zrmtxyafv"/><path class="u07qp3bhr"/><path class="kiz2lrbtx"/><path class="y_or9-s0p"/><path class="yqy8x4bvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:top-n-tune-duotone-regular" /></template>
<style>
.hnd7f4g6i {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 19h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kiz2lrbtx {
  d: path("M8 14h12");
}

.lkr_6zbxq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 14h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.salcojbrw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 9h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tokey8blw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 4h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u07qp3bhr {
  d: path("M8 9h12");
}

.y_or9-s0p {
  d: path("M8 19h12");
}

.yqy8x4bvc {
  d: path("M5.5 2H3v9h2.5");
}

.zn_kjwlsb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5.5 2H3v9h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zrmtxyafv {
  d: path("M8 4h12");
}

</style>
