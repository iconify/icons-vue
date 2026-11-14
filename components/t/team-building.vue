<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvx5ffb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:team-building" /></template>
<style>
.qvx5ffb_h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 12.5h5.5A1.75 1.75 0 0 1 12 14.25v5.5a1.75 1.75 0 0 1-1.75 1.75h-5.5A1.75 1.75 0 0 1 3 19.75v-5.5a1.75 1.75 0 0 1 1.75-1.75m9 0h5.5A1.75 1.75 0 0 1 21 14.25v5.5a1.75 1.75 0 0 1-1.75 1.75h-5.5A1.75 1.75 0 0 1 12 19.75v-5.5a1.75 1.75 0 0 1 1.75-1.75m-4.5-9h5.5a1.75 1.75 0 0 1 1.75 1.75v5.5a1.75 1.75 0 0 1-1.75 1.75h-5.5a1.75 1.75 0 0 1-1.75-1.75v-5.5A1.75 1.75 0 0 1 9.25 3.5m2.75 9v9m-4.5-9h9");
}

</style>
