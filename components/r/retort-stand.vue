<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea0i1-ere"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:retort-stand" /></template>
<style>
.ea0i1-ere {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 19H15a1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 15 21.5H5.5a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 5.5 19m2.25 0V2.5m0 5h7.5m0-3.5v10.5a2 2 0 0 0 4 0V4");
}

</style>
