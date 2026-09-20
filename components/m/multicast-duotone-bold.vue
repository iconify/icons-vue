<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rsea1pbos"/><path class="ujr3us5qo"/><path class="h3pl5fbyl"/><path class="hr57lpbwt"/><path class="n_5sjmbib"/><path class="x5sgl4bhi"/><path class="zuquf0b8s"/><path class="lymn1951z"/><path class="t6hm3zb9t"/><path class="qkyv2jo2z"/><path class="m1k1s7nte"/><path class="th_-hsbei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:multicast-duotone-bold" /></template>
<style>
.h3pl5fbyl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hr57lpbwt {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 5h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lymn1951z {
  d: path("M6 12h4");
}

.m1k1s7nte {
  d: path("M10 12h10");
}

.n_5sjmbib {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qkyv2jo2z {
  d: path("M10 5h10");
}

.rsea1pbos {
  fill: currentColor;
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

.t6hm3zb9t {
  d: path("M10 5v14");
}

.th_-hsbei {
  d: path("M10 19h10");
}

.ujr3us5qo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x5sgl4bhi {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 19h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zuquf0b8s {
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
