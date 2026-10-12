<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="rz2_ps6wq"/><path class="jp6asdbtm"/><path class="hsztyzb_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:release-tag-sharp" /></template>
<style>
.hsztyzb_n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.5 21.25v-6.5m-2.5 2.5l2.5-2.5l2.5 2.5");
}

.jp6asdbtm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 6.75h.01");
}

.rz2_ps6wq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.75H10l1.06 1.06l4.38 4.38l1.06 1.06l-1.06 1.06l-5.13 5.13l-1.06 1.06l-1.06-1.06l-4.38-4.38L2.75 10V2.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
