<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eq_hyg60b"/><path class="fze4jkbok"/><path class="m6o3bac1v"/><path class="o062g1b0a"/><path class="o0ozwgb-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:prefilter-duotone-thin" /></template>
<style>
.eq_hyg60b {
  fill: currentColor;
  d: path("M3 3h18l-7 7v5h-4v-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fze4jkbok {
  fill: currentColor;
  d: path("M12.5 17.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
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

.m6o3bac1v {
  d: path("M3 3h18l-7 7v5h-4v-5Z");
}

.o062g1b0a {
  d: path("M12.5 17.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.o0ozwgb-f {
  d: path("m18 20 2 2");
}

</style>
