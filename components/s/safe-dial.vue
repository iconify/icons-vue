<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="u3tk_h1oz"/><path class="l_ks21lnt"/><circle class="i2f29gznq"/><path class="hzlunw8gv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:safe-dial" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hzlunw8gv {
  d: path("M17.75 8.75v4");
}

.i2f29gznq {
  cx: 10.5px;
  cy: 10.75px;
  r: 3.5px;
}

.l_ks21lnt {
  d: path("M7 18.75v2.5m10-2.5v2.5");
}

.u3tk_h1oz {
  width: 17.5px;
  height: 16px;
  x: 3.25px;
  y: 2.75px;
  rx: 2.5px;
}

</style>
