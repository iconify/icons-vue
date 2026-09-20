<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="swquduh2r"/><path class="v07m3guvb"/><path class="b2zuoxbqm"/><path class="o8-8aibsp"/><path class="owl9kub7f"/><path class="b7nacdcee"/><path class="p2x4fkb_u"/><path class="pt-3kkb2k"/><path class="vd0jm7r_j"/><path class="p0o5ir5ue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sparse-search-duotone-thin" /></template>
<style>
.b2zuoxbqm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 11h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.b7nacdcee {
  d: path("M3 6h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o8-8aibsp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.owl9kub7f {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 16h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p0o5ir5ue {
  d: path("M15 16h6");
}

.p2x4fkb_u {
  d: path("M15 6h6");
}

.pt-3kkb2k {
  d: path("M9 11h6");
}

.swquduh2r {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v07m3guvb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vd0jm7r_j {
  d: path("M3 16h6");
}

</style>
