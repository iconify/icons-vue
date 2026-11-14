<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="carm-3b9v"/><path class="gkuzynynh"/><path class="e2k51acvp"/><path class="dgfhqybqf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:snowman" /></template>
<style>
.carm-3b9v {
  d: path("M8.5 6a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

.dgfhqybqf {
  d: path("M6.5 13L3 10m14.5 3l3.5-3");
}

.e2k51acvp {
  fill: currentColor;
  d: path("m15.5 5.25l3.5 1l-3.5 1Z");
}

.gkuzynynh {
  d: path("M6 15.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
