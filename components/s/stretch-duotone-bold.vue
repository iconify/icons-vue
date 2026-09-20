<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="oe3oa5b3b"/><path class="w08657bnd"/><path class="wrji4lgnj"/><path class="f5d6h4bjf"/><path class="zd1mml6it"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stretch-duotone-bold" /></template>
<style>
.f5d6h4bjf {
  d: path("m7 5 5 5 5 -5");
}

.oe3oa5b3b {
  fill: currentColor;
  d: path("M9 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
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

.w08657bnd {
  d: path("M9 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.wrji4lgnj {
  d: path("M12 8v7");
}

.zd1mml6it {
  d: path("m8 19 4 -4 4 4");
}

</style>
