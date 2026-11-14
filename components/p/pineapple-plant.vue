<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jltp27bbk"/><path class="fu8ua37vh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pineapple-plant" /></template>
<style>
.fu8ua37vh {
  d: path("M12 9.5c-1.25-2.5-1.25-4.75 0-7c1.25 2.25 1.25 4.5 0 7m-1.5 0c-2.5-.5-4-2.5-5-5c2.75.5 4.5 2.25 5 5m3 0c2.5-.5 4-2.5 5-5c-2.75.5-4.5 2.25-5 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jltp27bbk {
  d: path("M6.5 15.5a5.5 6 0 1 0 11 0a5.5 6 0 1 0-11 0m2.75-5.25L17 18M7 13l7.75 7.75m0-10.5L7 18m10-5l-7.75 7.75");
}

</style>
