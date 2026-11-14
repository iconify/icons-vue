<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jsztq_emy"/><path class="zoss28bin"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pet-weight" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jsztq_emy {
  d: path("M9.5 2.5h5a7 7 0 0 1 7 7v5a7 7 0 0 1-7 7h-5a7 7 0 0 1-7-7v-5a7 7 0 0 1 7-7");
}

.zoss28bin {
  d: path("M7.5 10a4.5 4.5 0 0 1 9 0Zm4.5 0l2.25-2.5M9.5 17.25a2.5 1.75 0 1 0 5 0a2.5 1.75 0 1 0-5 0m-.75-3h.01M12 13h.01m3.24 1.25h.01");
}

</style>
