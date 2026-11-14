<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tt2fo2bdk"/><path class="dxt0xxvoj"/><path class="bif6xt-xx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:repeat" /></template>
<style>
.bif6xt-xx {
  d: path("m8 13.5l-3 3l3 3");
}

.dxt0xxvoj {
  d: path("m16 4.5l3 3l-3 3m3.5.5v2.5a3 3 0 0 1-3 3H5");
}

.tt2fo2bdk {
  d: path("M4.5 13v-2.5a3 3 0 0 1 3-3H19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
