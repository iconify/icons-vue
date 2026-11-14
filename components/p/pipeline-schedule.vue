<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k2q427bcm"/><path class="x_z6wfbzp"/><path class="bk77kyrqo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pipeline-schedule" /></template>
<style>
.bk77kyrqo {
  d: path("M16.25 15.25h3.5A1.75 1.75 0 0 1 21.5 17v2.75a1.75 1.75 0 0 1-1.75 1.75h-3.5a1.75 1.75 0 0 1-1.75-1.75V17a1.75 1.75 0 0 1 1.75-1.75M16.5 14v2.25m3-2.25v2.25m-5 1.75h7");
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

.x_z6wfbzp {
  fill: currentColor;
  d: path("M7.5 3za.75.75 0 0 1 .75.75v8.5a.75.75 0 0 1-.75.75a.75.75 0 0 1-.75-.75v-8.5A.75.75 0 0 1 7.5 3m6.523 9.788q-.105.102-.241.157T13.5 13q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-8.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q13.426 3 13.5 3t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v8.5q0 .072-.014.144");
}

</style>
