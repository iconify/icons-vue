<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k2q427bcm"/><path class="cmgy7qc0w"/><path class="mp962dbqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pipeline-error" /></template>
<style>
.cmgy7qc0w {
  fill: currentColor;
  d: path("M7.5 3za.75.75 0 0 1 .75.75v8.5a.75.75 0 0 1-.75.75a.75.75 0 0 1-.75-.75v-8.5A.75.75 0 0 1 7.5 3m5.608 9.89q-.082-.051-.149-.12t-.113-.153t-.072-.178t-.024-.189v-8.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q13.426 3 13.5 3t.146.014t.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v8.5l-.001.04");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k2q427bcm {
  d: path("M5.75 5H3.5A1.5 1.5 0 0 0 2 6.5v3A1.5 1.5 0 0 0 3.5 11h2.25m3.5-6h2.5m-2.5 6h2.5m3.5-6h5.25A1.5 1.5 0 0 1 22 6.5v3a1.5 1.5 0 0 1-1.5 1.5h-5.25");
}

.mp962dbqn {
  d: path("m15 15l6 6m0-6l-6 6");
}

</style>
