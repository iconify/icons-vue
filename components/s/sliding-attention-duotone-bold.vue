<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x87wa6b5t"/><path class="lx3jyybfn"/><path class="ht9zq9bpv"/><path class="ycrqjrb3i"/><path class="b4x_isbqv"/><path class="d_6ujebpi"/><path class="x1_r36phd"/><path class="zy1jzxj5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sliding-attention-duotone-bold" /></template>
<style>
.b4x_isbqv {
  d: path("M8 6H5v12h3");
}

.d_6ujebpi {
  d: path("M16 6h3v12h-3");
}

.ht9zq9bpv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lx3jyybfn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 6h3v12h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x1_r36phd {
  d: path("M9 12h6");
}

.x87wa6b5t {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 6H5v12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ycrqjrb3i {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12.5 9.5 15 12l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zy1jzxj5t {
  d: path("M12.5 9.5 15 12l-2.5 2.5");
}

</style>
