<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="psz70bbgt"/><path class="uw5kuce7r"/><path class="sowhn7f6a"/><path class="v0nv9evjn"/><path class="m02rt1bwx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:motorsport-duotone-bold" /></template>
<style>
.m02rt1bwx {
  d: path("M13 14V9h7");
}

.psz70bbgt {
  fill: currentColor;
  d: path("M6 4h14v10H6Z");
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

.sowhn7f6a {
  d: path("M6 4h14v10H6Z");
}

.uw5kuce7r {
  d: path("M3 3v18");
}

.v0nv9evjn {
  d: path("M6 9h7V4");
}

</style>
