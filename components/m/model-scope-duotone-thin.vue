<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pc4ntbcgf"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="l0eqi9cfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:model-scope-duotone-thin" /></template>
<style>
.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l0eqi9cfe {
  d: path("m12 9 3 3 -3 3 -3 -3Z");
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.pc4ntbcgf {
  fill: currentColor;
  d: path("m12 9 3 3 -3 3 -3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
