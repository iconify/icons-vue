<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t_zdt5bjc"/><path class="d_mfrmbhj"/><path class="mlpjr3b8k"/><path class="j42rssb6i"/><path class="e2nq-yvbg"/><path class="gl3o38_gx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pine-tree-duotone-thin" /></template>
<style>
.d_mfrmbhj {
  fill: currentColor;
  d: path("m4 15 8 -8 8 8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.e2nq-yvbg {
  d: path("M12 15v6");
}

.gl3o38_gx {
  d: path("M8 21h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j42rssb6i {
  d: path("m4 15 8 -8 8 8Z");
}

.mlpjr3b8k {
  d: path("m6 9 6 -6 6 6Z");
}

.t_zdt5bjc {
  fill: currentColor;
  d: path("m6 9 6 -6 6 6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
