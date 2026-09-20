<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qrdwmtbvi"/><path class="w6zihnbcy"/><path class="vrecxx6kh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:toothbrush-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qrdwmtbvi {
  d: path("M9 3h6v7H9Z");
}

.vrecxx6kh {
  d: path("M9 6h6");
}

.w6zihnbcy {
  d: path("M12 10v11");
}

</style>
