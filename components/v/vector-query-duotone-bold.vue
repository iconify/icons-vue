<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ph4toqkti"/><path class="wko3ej0az"/><path class="r0oiw3llx"/><path class="s7h04rdua"/><path class="skm9b1j-d"/><path class="ls7ugdcwr"/><path class="fglxyivky"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:vector-query-duotone-bold" /></template>
<style>
.fglxyivky {
  d: path("M18 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ls7ugdcwr {
  d: path("M6 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ph4toqkti {
  fill: currentColor;
  d: path("M4 9a5 5 0 1 0 10 0A5 5 0 1 0 4 9");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.r0oiw3llx {
  fill: currentColor;
  d: path("M18 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

.s7h04rdua {
  d: path("M4 9a5 5 0 1 0 10 0A5 5 0 1 0 4 9");
}

.skm9b1j-d {
  d: path("m13 13 6 6");
}

.wko3ej0az {
  fill: currentColor;
  d: path("M6 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
