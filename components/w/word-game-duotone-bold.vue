<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rh_yjfbed"/><path class="r8lmp6u5e"/><path class="xyvnrdm2l"/><path class="gszsvr09c"/><path class="s_sj9bjbj"/><path class="izycrzbmp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:word-game-duotone-bold" /></template>
<style>
.gszsvr09c {
  d: path("M14 6v12h7V6Z");
}

.izycrzbmp {
  d: path("M16 14h3");
}

.r8lmp6u5e {
  fill: currentColor;
  d: path("M14 6v12h7V6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rh_yjfbed {
  fill: currentColor;
  d: path("M3 6v12h7V6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s_sj9bjbj {
  d: path("m4.5 14 2 -2 2 2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xyvnrdm2l {
  d: path("M3 6v12h7V6Z");
}

</style>
