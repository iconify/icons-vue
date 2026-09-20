<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h1p6rhblx"/><path class="af7iv3n-p"/><path class="iiquwwbvb"/><path class="jnf_2db5t"/><path class="n_1n94xtx"/><path class="mvm7r4bea"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stop-loss-duotone-thin" /></template>
<style>
.af7iv3n-p {
  d: path("M12 2v2.5");
}

.h1p6rhblx {
  fill: currentColor;
  d: path("M5 6.5a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2V16a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
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

.iiquwwbvb {
  d: path("M5 6.5a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2V16a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

.jnf_2db5t {
  d: path("M12 18v3");
}

.mvm7r4bea {
  d: path("M8 14h8");
}

.n_1n94xtx {
  d: path("M9.5 8.5 12 11l2.5 -2.5");
}

</style>
