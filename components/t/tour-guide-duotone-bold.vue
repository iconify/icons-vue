<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vdkk_bbqh"/><path class="jy2rzibrh"/><path class="loxcusk2q"/><path class="ou_6febrd"/><path class="c27cgq4un"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tour-guide-duotone-bold" /></template>
<style>
.c27cgq4un {
  d: path("M18 8v8");
}

.jy2rzibrh {
  d: path("M6 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.loxcusk2q {
  d: path("M2 21a7 7 0 0 1 14 0");
}

.ou_6febrd {
  d: path("M14 8a4 4 0 0 1 8 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vdkk_bbqh {
  fill: currentColor;
  d: path("M6 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
