<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v4v3k2b7i"/><path class="eff5yibna"/><path class="ir_a00ama"/><path class="h1f6hnbpb"/><path class="xt3sjtb4p"/><path class="pq9ly31-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sports-day-duotone-thin" /></template>
<style>
.eff5yibna {
  fill: currentColor;
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.h1f6hnbpb {
  d: path("M2 21v-8h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ir_a00ama {
  d: path("M8 21V8h8v13Z");
}

.pq9ly31-r {
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.v4v3k2b7i {
  fill: currentColor;
  d: path("M8 21V8h8v13Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xt3sjtb4p {
  d: path("M16 13h6v8");
}

</style>
