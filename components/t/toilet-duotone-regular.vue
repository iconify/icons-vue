<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l8n_uacwg"/><path class="vu337ub9w"/><path class="y1fttzc7x"/><path class="cn55ckwew"/><path class="jnf_2db5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:toilet-duotone-regular" /></template>
<style>
.cn55ckwew {
  d: path("M5 10h14v3a7.4 7.4 0 0 1 -14 0Z");
}

.jnf_2db5t {
  d: path("M12 18v3");
}

.l8n_uacwg {
  fill: currentColor;
  d: path("M5 2v5h8V2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vu337ub9w {
  fill: currentColor;
  d: path("M5 10h14v3a7.4 7.4 0 0 1 -14 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.y1fttzc7x {
  d: path("M5 2v5h8V2Z");
}

</style>
