<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gq9cppbqx"/><path class="hvq_ui2bc"/><path class="lusy41b0m"/><path class="vrp3h-b8z"/><path class="c8uh2gw9u"/><path class="mss3k8l1q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:science-experiment-duotone-thin" /></template>
<style>
.c8uh2gw9u {
  d: path("M9 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.gq9cppbqx {
  fill: currentColor;
  d: path("M10 3h4v5.5a6.5 6.5 0 1 1 -4 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hvq_ui2bc {
  fill: currentColor;
  d: path("M9 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.lusy41b0m {
  fill: currentColor;
  d: path("M12.5 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mss3k8l1q {
  d: path("M12.5 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.vrp3h-b8z {
  d: path("M10 3h4v5.5a6.5 6.5 0 1 1 -4 0Z");
}

</style>
