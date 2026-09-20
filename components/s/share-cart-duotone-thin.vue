<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a-gugwb5v"/><path class="rviuo_bhz"/><path class="c8ewb5pjd"/><path class="bpciasb2z"/><path class="c11_n0b6s"/><path class="k3juqlbuw"/><path class="ehhh0cbfh"/><path class="d-sfu0byc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:share-cart-duotone-thin" /></template>
<style>
.a-gugwb5v {
  fill: currentColor;
  d: path("M3 5.5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.bpciasb2z {
  d: path("M3 5.5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.c11_n0b6s {
  d: path("M6.5 19.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.c8ewb5pjd {
  fill: currentColor;
  d: path("M15.5 19.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.d-sfu0byc {
  d: path("M11.5 7.5H15V11");
}

.ehhh0cbfh {
  d: path("m9 13.5 6 -6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k3juqlbuw {
  d: path("M15.5 19.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.rviuo_bhz {
  fill: currentColor;
  d: path("M6.5 19.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
