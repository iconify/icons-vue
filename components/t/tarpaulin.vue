<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="t-tumzbdy"/><path class="j06rmveig"/><path class="js43zsbza"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tarpaulin" /></template>
<style>
.j06rmveig {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 7.75h.01m5.49 0h.01m5.49 0h.01");
}

.js43zsbza {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.75 16.25l5-4");
}

.t-tumzbdy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4.5h18c0 5 .1 10 .25 15.25c-3 .75-6.5.25-9.25-.25s-6.25-.25-9.25.25C2.9 14.5 3 9.5 3 4.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
