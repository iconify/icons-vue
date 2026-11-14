<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjzr-gbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:snow-pit" /></template>
<style>
.fjzr-gbwk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5v15a2 2 0 0 0 2 2h13a2 2 0 0 0 2-2v-15m-17 3h17m-17 4h17M3.5 17h17M14 13.75h8");
}

</style>
