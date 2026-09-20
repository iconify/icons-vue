<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ddf9nt86r"/><path class="zw76b7msm"/><path class="oh4p-ccfe"/><path class="jlpxneb5g"/><path class="pqrd0wbvk"/><path class="okg0-qwlz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:segmented-duotone-thin" /></template>
<style>
.ddf9nt86r {
  fill: currentColor;
  d: path("M2 10a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
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

.jlpxneb5g {
  d: path("M9 8v8");
}

.oh4p-ccfe {
  d: path("M2 10a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.okg0-qwlz {
  d: path("M4.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.pqrd0wbvk {
  d: path("M15 8v8");
}

.zw76b7msm {
  fill: currentColor;
  d: path("M4.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
