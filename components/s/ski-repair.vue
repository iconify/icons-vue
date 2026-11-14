<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5tfqackc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ski-repair" /></template>
<style>
.t5tfqackc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 20.5l13-13c1-1 2-2.5 2-4c-1.5 0-3 1-4 2l-13 13a1.5 1.5 0 0 0 2 2m13.75-6A2.25 2.25 0 1 1 17 16.75m-2.25 4.5l3-3");
}

</style>
