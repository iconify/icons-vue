<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="uf_erdb7p"/><path class="kf_mvwa8r"/><rect class="kbiyl04tr"/><path class="ss_kmjbmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-card" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kbiyl04tr {
  width: 6.5px;
  height: 5px;
  x: 14.75px;
  y: 8.25px;
  rx: 1px;
}

.kf_mvwa8r {
  d: path("M4 20.25h11a.75.75 0 0 0 .75-.75c0-3-2.8-5.25-6.25-5.25S3.25 16.5 3.25 19.5a.75.75 0 0 0 .75.75");
}

.ss_kmjbmm {
  d: path("M16.5 10.75h3");
}

.uf_erdb7p {
  cx: 9px;
  cy: 7.75px;
  r: 3.5px;
}

</style>
