<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g55pkgb9q"/><path class="uxvy-ac8l"/><path class="d8abqfbpc"/><path class="fhtr4ivmi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:threshold-duotone-bold" /></template>
<style>
.d8abqfbpc {
  d: path("M3 11h18");
}

.fhtr4ivmi {
  d: path("m4 18 6 -6 4 4 6 -6");
}

.g55pkgb9q {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 11h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uxvy-ac8l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m4 18 6 -6 4 4 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
