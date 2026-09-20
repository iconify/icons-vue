<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nveb10bds"/><path class="r16vkbcll"/><path class="mpqh2s_-m"/><path class="s-l_glb5y"/><path class="s3axsdb5n"/><path class="j7gva9flg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sandbox-escape-alert-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j7gva9flg {
  d: path("M16.5 19.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.mpqh2s_-m {
  d: path("M3 11a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.nveb10bds {
  fill: currentColor;
  d: path("M3 11a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.r16vkbcll {
  fill: currentColor;
  d: path("M16.5 19.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s-l_glb5y {
  d: path("M19 4.83a3.5 3.5 0 1 1 -2.96 0");
}

.s3axsdb5n {
  d: path("M17.5 14v2.5");
}

</style>
