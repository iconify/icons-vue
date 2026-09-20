<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="evhc9nlqu"/><path class="z3esnob7f"/><path class="prbs3ccnp"/><path class="eki_s5bnj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:turn-right-duotone-thin" /></template>
<style>
.eki_s5bnj {
  d: path("m14 6 3 3 -3 3");
}

.evhc9nlqu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 21V9h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.prbs3ccnp {
  d: path("M8 21V9h9");
}

.z3esnob7f {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 6 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
