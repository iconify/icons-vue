<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="s_z-4bu9m"/><path class="b4x_isbqv"/><path class="d_6ujebpi"/><path class="kcomyoe5y"/><path class="lhus_vb3v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:state-lock-duotone-bold" /></template>
<style>
.b4x_isbqv {
  d: path("M8 6H5v12h3");
}

.d_6ujebpi {
  d: path("M16 6h3v12h-3");
}

.kcomyoe5y {
  d: path("M9 12h6v3H9Z");
}

.lhus_vb3v {
  d: path("M10.5 12a1.5 1.5 0 0 1 3 0");
}

.s_z-4bu9m {
  fill: currentColor;
  d: path("M9 12h6v3H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
