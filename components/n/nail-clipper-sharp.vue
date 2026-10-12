<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="oxm88x9bd"/><path class="huyutybox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nail-clipper-sharp" /></template>
<style>
.huyutybox {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.75 16.25h.01");
}

.oxm88x9bd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 14.25h15.5v4H2.75zM5.5 12l15.25-4.25M14 13.5v-3.1");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
