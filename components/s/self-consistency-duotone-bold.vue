<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="oojvcccnq"/><path class="k0l21tbkp"/><path class="j-oq7nbpn"/><path class="hao-u2bvu"/><path class="ds000fbnl"/><path class="bj2hlhbfp"/><path class="ukjt4fb6s"/><path class="ids981bkm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:self-consistency-duotone-bold" /></template>
<style>
.bj2hlhbfp {
  d: path("M3 12h12");
}

.ds000fbnl {
  d: path("M3 7h12");
}

.hao-u2bvu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m17 11 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ids981bkm {
  d: path("m17 11 2 2 3 -3");
}

.j-oq7nbpn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 17h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k0l21tbkp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oojvcccnq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 7h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ukjt4fb6s {
  d: path("M3 17h12");
}

</style>
