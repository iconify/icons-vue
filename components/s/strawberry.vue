<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w7-x-cbch"/><path class="t_96fdq-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:strawberry" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t_96fdq-n {
  d: path("m9 5l3 2.5L15 5m-5 7h.01M14 12h.01M12 16h.01");
}

.w7-x-cbch {
  d: path("M12 7.5c-5-1-7.5 2-6.5 5.5s4.5 7.5 6.5 8c2-.5 5.5-4.5 6.5-8S17 6.5 12 7.5");
}

</style>
