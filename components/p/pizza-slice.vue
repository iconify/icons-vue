<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="kba-g5dhs"/><path class="kjslsjdfn"/><path class="bj9nzfb4r"/><path class="mi7a68b3f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pizza-slice" /></template>
<style>
.bj9nzfb4r {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 10.25v-7A7.75 7.75 0 0 1 20.75 11h-7a.75.75 0 0 1-.75-.75");
}

.kba-g5dhs {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 5.75v7a.75.75 0 0 0 .75.75h7a7.75 7.75 0 1 1-7.75-7.75m-.75 7.75h-7m7.75.75v7");
}

.kjslsjdfn {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 10h.01m-.26 7h.01m7.49.5h.01");
}

.mi7a68b3f {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 5.75A5.25 5.25 0 0 1 18.25 11");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
