<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><circle class="jty_abcpu"/><path class="so69kfbvn"/><path class="wbw_ixbrw"/><ellipse class="yad62e0rw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smile-circle-line-duotone" /></template>
<style>
.jty_abcpu {
  cx: 12px;
  cy: 12px;
  r: 10px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  opacity: var(--svg-opacity--0-5, 0.5);
}

.pr52f_b5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
}

.so69kfbvn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 16C9.85038 16.6303 10.8846 17 12 17C13.1154 17 14.1496 16.6303 15 16");
}

.wbw_ixbrw {
  d: path("M15.5 10.5C15.5 11.0523 15.2761 11.5 15 11.5C14.7239 11.5 14.5 11.0523 14.5 10.5C14.5 9.94772 14.7239 9.5 15 9.5C15.2761 9.5 15.5 9.94772 15.5 10.5Z");
}

.yad62e0rw {
  cx: 9px;
  cy: 10.5px;
  rx: 0.5px;
  ry: 1px;
}

</style>
