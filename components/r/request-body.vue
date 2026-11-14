<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ktvep6pgg"/><path class="tufj21bif"/><path class="rp4oqibyb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:request-body" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ktvep6pgg {
  d: path("M4 10v9a2.5 2.5 0 0 0 2.5 2.5h11A2.5 2.5 0 0 0 20 19v-9");
}

.rp4oqibyb {
  d: path("M10.25 10.25L13 13l2.75-2.75M8.5 17.5h8");
}

.tufj21bif {
  d: path("M3 4.5h6a4 4 0 0 1 4 4V13");
}

</style>
