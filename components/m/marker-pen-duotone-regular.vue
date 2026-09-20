<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d_ck1z3vq"/><path class="nbr-9yb3l"/><path class="yigkywbyn"/><path class="ry5l7ebuo"/><path class="ot37jibbb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:marker-pen-duotone-regular" /></template>
<style>
.d_ck1z3vq {
  fill: currentColor;
  d: path("m8 14 8 -8 4 4 -8 8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nbr-9yb3l {
  fill: currentColor;
  d: path("m5 17 3 -3 4 4 -3 3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ot37jibbb {
  d: path("m10 16 4 -4");
}

.ry5l7ebuo {
  d: path("m5 17 3 -3 4 4 -3 3Z");
}

.yigkywbyn {
  d: path("m8 14 8 -8 4 4 -8 8Z");
}

</style>
