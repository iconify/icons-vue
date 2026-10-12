<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w9m98cbgx"/><rect class="rc2do_1ou"/><circle class="adcsmfg4s"/><path class="ql3az4bsr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:navigation-light" /></template>
<style>
.adcsmfg4s {
  cx: 12px;
  cy: 11.75px;
  r: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ql3az4bsr {
  d: path("M7.25 17h9.5v2.5A1.75 1.75 0 0 1 15 21.25H9a1.75 1.75 0 0 1-1.75-1.75Zm-4.5-5.25h2.5m13.5 0h2.5m-18-5l2.5 1.5m15-1.5l-2.5 1.5m-15 8.5l2.5-1.5m15 1.5l-2.5-1.5");
}

.rc2do_1ou {
  width: 8.5px;
  height: 10.5px;
  x: 7.75px;
  y: 6.5px;
  rx: 1px;
}

.w9m98cbgx {
  d: path("M7.25 6.5h9.5L15 3.5H9Z");
}

</style>
