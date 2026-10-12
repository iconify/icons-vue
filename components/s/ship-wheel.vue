<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tvf_arbig"/><circle class="rzyzgqcqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ship-wheel" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rzyzgqcqn {
  cx: 12px;
  cy: 12px;
  r: 2.25px;
}

.tvf_arbig {
  d: path("M12 5.75a6.25 6.25 0 1 0 0 12.5a6.25 6.25 0 1 0 0-12.5M14.25 12h7m-7.66 1.59l4.95 4.95M12 14.25v7m-1.59-7.66l-4.95 4.95M9.75 12h-7m7.66-1.59L5.46 5.46M12 9.75v-7m1.59 7.66l4.95-4.95");
}

</style>
