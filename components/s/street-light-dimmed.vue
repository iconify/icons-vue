<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kwghr-02h"/><path class="nxp856bhb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:street-light-dimmed" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kwghr-02h {
  d: path("M4 21h6m-3 0V9m0 0a6 6 0 0 1 6-6m1.016 0h3.968A1.17 1.17 0 0 1 19 4.75l-.568.994a1.5 1.5 0 0 1-1.302.756h-2.26a1.5 1.5 0 0 1-1.302-.756L13 4.75A1.17 1.17 0 0 1 14.016 3M15 18.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

.nxp856bhb {
  fill: currentColor;
  d: path("M18.5 15a3.5 3.5 0 0 1 0 7Z");
}

</style>
