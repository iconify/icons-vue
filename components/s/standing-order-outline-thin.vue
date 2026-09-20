<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k6fi9qmtq"/><path class="ozi-k-boi"/><path class="l0v-b4kbr"/><path class="qn0soqduf"/><path class="wtzvy2bax"/><path class="lnvqc4bfd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:standing-order-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k6fi9qmtq {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.l0v-b4kbr {
  d: path("M8 12h8");
}

.lnvqc4bfd {
  d: path("m10 14.5 -2 2 2 2");
}

.ozi-k-boi {
  d: path("M3 7h18");
}

.qn0soqduf {
  d: path("m14 10 2 2 -2 2");
}

.wtzvy2bax {
  d: path("M8 16.5h8");
}

</style>
