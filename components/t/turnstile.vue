<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="b6v80u5tr"/><path class="jcden9bsz"/><circle class="viz6w_9zv"/><path class="lpsd57b6z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:turnstile" /></template>
<style>
.b6v80u5tr {
  width: 6.5px;
  height: 13px;
  x: 3.5px;
  y: 8.25px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jcden9bsz {
  d: path("M5.5 11.25H8");
}

.lpsd57b6z {
  d: path("M13.5 11.5h7.75m-8.62-1.52l3.75-6.5m-3.75 9.54l3.75 6.5");
}

.viz6w_9zv {
  cx: 11.75px;
  cy: 11.5px;
  r: 1.75px;
}

</style>
