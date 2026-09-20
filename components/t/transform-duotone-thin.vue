<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lsm3wwbsc"/><path class="bcd4ip6hz"/><path class="sjmvcxbpe"/><path class="l0v-b4kbr"/><path class="ug4kkubvk"/><path class="ipv0cebdm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:transform-duotone-thin" /></template>
<style>
.bcd4ip6hz {
  fill: currentColor;
  d: path("M13 16a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ipv0cebdm {
  d: path("M13 16a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.l0v-b4kbr {
  d: path("M8 12h8");
}

.lsm3wwbsc {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.sjmvcxbpe {
  d: path("M2 6a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.ug4kkubvk {
  d: path("m13 9 3 3 -3 3");
}

</style>
