<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r0-aom3qb"/><path class="nnzlfsekh"/><path class="d2gpzsh-s"/><path class="a62njb70e"/><path class="wp0aeb9st"/><path class="b58isb55w"/><path class="lo0rkwbmg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:piano-duotone-bold" /></template>
<style>
.a62njb70e {
  d: path("M15 6v12");
}

.b58isb55w {
  d: path("M12 6v7");
}

.d2gpzsh-s {
  d: path("M9 6v12");
}

.lo0rkwbmg {
  d: path("M18 6v7");
}

.nnzlfsekh {
  d: path("M2 8a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.r0-aom3qb {
  fill: currentColor;
  d: path("M2 8a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
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

.wp0aeb9st {
  d: path("M6 6v7");
}

</style>
