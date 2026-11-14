<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p9cwjedbk"/><path class="ky2f7t9jd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:recovery-facility" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ky2f7t9jd {
  d: path("m11.75 19.25l1.75-1.75l1.75 1.75");
}

.p9cwjedbk {
  d: path("M9.234 18H2.5V9l4 2.5V9l4 2.5v-9h3v12.166m4-1.166a4 4 0 1 1-4 4");
}

</style>
