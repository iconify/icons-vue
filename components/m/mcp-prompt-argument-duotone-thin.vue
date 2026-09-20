<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kq4n_h3_b"/><path class="s_qzku-2n"/><path class="s09hy0b0y"/><path class="xq_z6abtw"/><path class="wv2epfb5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mcp-prompt-argument-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kq4n_h3_b {
  fill: currentColor;
  d: path("M14 5h4a3 3 0 0 1 3 3v8a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V8l3 -3h4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s_qzku-2n {
  d: path("M14 5h4a3 3 0 0 1 3 3v8a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V8l3 -3h4");
}

.s09hy0b0y {
  d: path("M7 11h10");
}

.wv2epfb5m {
  d: path("M14 15h3");
}

.xq_z6abtw {
  d: path("M7 15h4");
}

</style>
