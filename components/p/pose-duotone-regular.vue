<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eff5yibna"/><path class="bjn8jkb3z"/><path class="hkk_59byn"/><path class="s400aq5bd"/><path class="abmzqpbwt"/><path class="fytwd7bsj"/><path class="pq9ly31-r"/><path class="wgmj3x5ib"/><path class="h_yag6b0i"/><path class="zc1w0xe2t"/><path class="qv5w5objz"/><path class="c7u43zhgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pose-duotone-regular" /></template>
<style>
.abmzqpbwt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 14 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bjn8jkb3z {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 6v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c7u43zhgq {
  d: path("m12 14 5 5");
}

.eff5yibna {
  fill: currentColor;
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fytwd7bsj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 14 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h_yag6b0i {
  d: path("m12 8 -5 5");
}

.hkk_59byn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 8 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pq9ly31-r {
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.qv5w5objz {
  d: path("m12 14 -5 5");
}

.s400aq5bd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 8 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wgmj3x5ib {
  d: path("M12 6v8");
}

.zc1w0xe2t {
  d: path("m12 8 5 5");
}

</style>
