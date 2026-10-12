<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o_vcm4blu"/><path class="u9f0elhni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:timer-reset" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o_vcm4blu {
  d: path("M12.93 20.86a7.5 7.5 0 1 1 5.81-9.3M9.25 2.75h4.5m-2.25 0V6");
}

.u9f0elhni {
  d: path("M11.5 13.5V9.25a4.25 4.25 0 0 1 4.25 4.25Zm4.5 5a2.5 2.5 0 1 0 2.5-2.5m1.25-1.25L18.5 16l1.25 1.25");
}

</style>
