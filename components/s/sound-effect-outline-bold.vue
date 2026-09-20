<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="v_bqwbcfx"/><path class="kat3by1wu"/><path class="izng5ebil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sound-effect-outline-bold" /></template>
<style>
.izng5ebil {
  d: path("M18.24 8.76a6 6 0 0 1 0 8.5");
}

.kat3by1wu {
  d: path("M16.12 10.88a3 3 0 0 1 0 4.24");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v_bqwbcfx {
  d: path("m11 5 -5 5h4l-5 5");
}

</style>
