<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uobwinb1c"/><path class="xbfxmobjr"/><path class="urzylvb1v"/><path class="iqnqxwbgv"/><path class="yc7uj-bdi"/><path class="lzyo_l7yh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:weight-prune-outline-bold" /></template>
<style>
.iqnqxwbgv {
  d: path("m7.5 10 2.5 2.5");
}

.lzyo_l7yh {
  d: path("m14.5 9 3 3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uobwinb1c {
  d: path("M2 7.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.urzylvb1v {
  d: path("M9 14.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.xbfxmobjr {
  d: path("M16 7.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.yc7uj-bdi {
  d: path("M16.5 10 14 12.5");
}

</style>
