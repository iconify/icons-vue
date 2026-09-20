<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m_pa0sbgw"/><path class="qvx9grz6m"/><path class="fkv80ihsm"/><path class="c3qjvtbje"/><path class="p4xo-obtz"/><path class="b7nacdcee"/><path class="p2x4fkb_u"/><path class="pt-3kkb2k"/><path class="vd0jm7r_j"/><path class="p0o5ir5ue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sparse-search-duotone-bold" /></template>
<style>
.b7nacdcee {
  d: path("M3 6h6");
}

.c3qjvtbje {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fkv80ihsm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 11h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m_pa0sbgw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p0o5ir5ue {
  d: path("M15 16h6");
}

.p2x4fkb_u {
  d: path("M15 6h6");
}

.p4xo-obtz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 16h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pt-3kkb2k {
  d: path("M9 11h6");
}

.qvx9grz6m {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vd0jm7r_j {
  d: path("M3 16h6");
}

</style>
