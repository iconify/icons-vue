<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_8_l-adg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:water-the-plants" /></template>
<style>
.j_8_l-adg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.634 5.969l1.732 1a3.5 3.5 0 0 1 1.281 4.781a3.5 3.5 0 0 1-4.781 1.281l-1.732-1A3.5 3.5 0 0 1 4.853 7.25a3.5 3.5 0 0 1 4.781-1.281m-1.732-1l1.375-2.382l4.33 2.5l-1.375 2.382m1.018 3.281l4.5 1m-.25 2.75h.01m2.74-.75h.01m-2.51 7.75v-2.25m0 0q0-2.25-2.75-2.5q0 2.5 2.75 2.5m0 0q0-2.25 2.75-2.5q0 2.5-2.75 2.5");
}

</style>
