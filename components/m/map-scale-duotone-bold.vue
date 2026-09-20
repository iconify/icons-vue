<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g55pkgb9q"/><path class="bzmzml3bu"/><path class="riogcmb0z"/><path class="db4nonbww"/><path class="ud-xiac5d"/><path class="d8abqfbpc"/><path class="h_c4fk0bb"/><path class="l3hfq7bhw"/><path class="gjmq94baq"/><path class="lfyekl_xx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:map-scale-duotone-bold" /></template>
<style>
.bzmzml3bu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d8abqfbpc {
  d: path("M3 11h18");
}

.db4nonbww {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 11v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g55pkgb9q {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 11h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gjmq94baq {
  d: path("M15 11v4");
}

.h_c4fk0bb {
  d: path("M3 11v6");
}

.l3hfq7bhw {
  d: path("M9 11v4");
}

.lfyekl_xx {
  d: path("M21 11v6");
}

.riogcmb0z {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 11v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ud-xiac5d {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
