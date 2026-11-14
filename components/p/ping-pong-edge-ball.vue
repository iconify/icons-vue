<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mci_zup0z"/><path class="sughdnbhv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ping-pong-edge-ball" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mci_zup0z {
  d: path("m3.585 15.829l2-4A1.5 1.5 0 0 1 6.927 11h12.146a1.5 1.5 0 0 1 1.342 2.171l-2 4a1.5 1.5 0 0 1-1.342.829H4.927a1.5 1.5 0 0 1-1.342-2.171");
}

.sughdnbhv {
  d: path("M16 8a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-5.75 10l3.5-7");
}

</style>
