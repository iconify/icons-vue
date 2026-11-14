<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="byierzvjp"/><path class="skqhp0x2q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tennis-scoreboard" /></template>
<style>
.byierzvjp {
  d: path("M6 3h12a3.5 3.5 0 0 1 3.5 3.5v7A3.5 3.5 0 0 1 18 17H6a3.5 3.5 0 0 1-3.5-3.5v-7A3.5 3.5 0 0 1 6 3m1 14v4m10-4v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.skqhp0x2q {
  d: path("M7 6h.5a1.75 1.75 0 0 1 1.75 1.75v4.5A1.75 1.75 0 0 1 7.5 14H7a1.75 1.75 0 0 1-1.75-1.75v-4.5A1.75 1.75 0 0 1 7 6m9.5 0h.5a1.75 1.75 0 0 1 1.75 1.75v4.5A1.75 1.75 0 0 1 17 14h-.5a1.75 1.75 0 0 1-1.75-1.75v-4.5A1.75 1.75 0 0 1 16.5 6");
}

</style>
