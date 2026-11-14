<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfs6-1yza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:starting-line" /></template>
<style>
.gfs6-1yza {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3v14M8.5 3.5h7.195a1.06 1.06 0 0 1 .805 1.75l-.663.774a1.5 1.5 0 0 0 0 1.952l.663.774a1.06 1.06 0 0 1-.805 1.75H8.5A1.5 1.5 0 0 1 7 9V5a1.5 1.5 0 0 1 1.5-1.5M2.5 20H6m3.5 0h5m3.5 0h3.5");
}

</style>
