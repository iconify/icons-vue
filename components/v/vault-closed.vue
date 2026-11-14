<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="th7t3outk"/><path class="r5gjvcc4i"/><path class="sw_-hqbmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vault-closed" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r5gjvcc4i {
  d: path("M3.25 7.25zA1.25 1.25 0 0 1 4.5 8.5v.25A1.25 1.25 0 0 1 3.25 10A1.25 1.25 0 0 1 2 8.75V8.5a1.25 1.25 0 0 1 1.25-1.25m0 6.75za1.25 1.25 0 0 1 1.25 1.25v.25a1.25 1.25 0 0 1-1.25 1.25A1.25 1.25 0 0 1 2 15.5v-.25A1.25 1.25 0 0 1 3.25 14m5-2a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0");
}

.sw_-hqbmm {
  d: path("M11 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m1.5-1.5V6m1.25 6.75l4 2.25m-6.5-2.25l-4 2.25");
}

.th7t3outk {
  d: path("M3.75 12a8.75 8.75 0 1 0 17.5 0a8.75 8.75 0 1 0-17.5 0");
}

</style>
