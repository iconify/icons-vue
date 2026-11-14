<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q7ggq2bon"/><path class="f7wo-0bvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shamrock" /></template>
<style>
.f7wo-0bvs {
  d: path("m12 11l-3.25 3.25A2.3 2.3 0 0 1 5.5 11a2.3 2.3 0 0 1 3.25-3.25Zm0 0l3.25-3.25A2.3 2.3 0 0 1 18.5 11a2.3 2.3 0 0 1-3.25 3.25Zm0 0q.5 6 3 9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q7ggq2bon {
  d: path("M12 11L8.75 7.75A2.3 2.3 0 0 1 12 4.5a2.3 2.3 0 0 1 3.25 3.25Z");
}

</style>
