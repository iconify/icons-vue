<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="d4rfzbb0c"/><path class="bx_argeyt"/><path class="upu8uhb6u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:user-consent-outline-bold" /></template>
<style>
.bx_argeyt {
  d: path("M4 15a4 4 0 0 1 8 0");
}

.d4rfzbb0c {
  d: path("M6 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.upu8uhb6u {
  d: path("m14 13 2 2 3.5 -3.5");
}

</style>
