<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mzsthfbrb"/><path class="unqnlsccq"/><path class="yzbvbzaxy"/><path class="nzpsuduik"/><path class="j835zw5-z"/><path class="kd8ucebka"/><path class="fd_yklwbw"/><path class="x-e8q2nft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:oven-duotone-thin" /></template>
<style>
.fd_yklwbw {
  d: path("M16 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j835zw5-z {
  d: path("M3 9h18");
}

.kd8ucebka {
  d: path("M6 6h8");
}

.mzsthfbrb {
  fill: currentColor;
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nzpsuduik {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.unqnlsccq {
  fill: currentColor;
  d: path("M16 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.x-e8q2nft {
  d: path("M7 12h10v6H7Z");
}

.yzbvbzaxy {
  fill: currentColor;
  d: path("M7 12h10v6H7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
