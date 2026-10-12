<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="zrqdoic4z"/><path class="kvy9_u7vj"/><path class="o0w7y1jzr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:scoreboard" /></template>
<style>
.kvy9_u7vj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 17.75v3.5m9-3.5v3.5m-10.75-12a1.75 1.75 0 0 1 3.5 0c0 1.5-3.5 3-3.5 5h3.5m6-5.5L17 7.5v6.75");
}

.o0w7y1jzr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9.25h.01m-.01 3.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zrqdoic4z {
  width: 18.5px;
  height: 14px;
  x: 2.75px;
  y: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

</style>
