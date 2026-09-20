<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rvz2lnbll"/><path class="xbdnj9ayw"/><path class="r0fx73bms"/><path class="xlptirb6n"/><path class="keqc2pbxm"/><path class="ph-bhccoq"/><path class="igam7_b3d"/><path class="hlqoyz1hh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:people-group-duotone-bold" /></template>
<style>
.hlqoyz1hh {
  d: path("M3 20a9 9 0 0 1 18 0");
}

.igam7_b3d {
  d: path("M16 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.keqc2pbxm {
  d: path("M4 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ph-bhccoq {
  d: path("M10 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.r0fx73bms {
  fill: currentColor;
  d: path("M16 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rvz2lnbll {
  fill: currentColor;
  d: path("M4 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

.xbdnj9ayw {
  fill: currentColor;
  d: path("M10 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xlptirb6n {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 20a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
