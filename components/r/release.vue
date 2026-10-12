<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="hlhm7wb1n"/><path class="jp6asdbtm"/><path class="hsztyzb_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:release" /></template>
<style>
.hlhm7wb1n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.75H8.5q1.5 0 2.56 1.06l4.38 4.38q1.06 1.06 0 2.12l-5.13 5.13q-1.06 1.06-2.12 0l-4.38-4.38Q2.75 10 2.75 8.5V4.25q0-1.5 1.5-1.5");
}

.hsztyzb_n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.5 21.25v-6.5m-2.5 2.5l2.5-2.5l2.5 2.5");
}

.jp6asdbtm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 6.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
