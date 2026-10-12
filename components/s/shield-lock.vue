<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cm8lo6v1l"/><rect class="qutlwjb1x"/><path class="hei0_l2rx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shield-lock" /></template>
<style>
.cm8lo6v1l {
  d: path("m12 2.75l6.6 2.45a1 1 0 0 1 .65.94v5.26c0 4.4-2.9 7.6-7.25 9.85C7.65 19 4.75 15.8 4.75 11.4V6.14a1 1 0 0 1 .65-.94Z");
}

.hei0_l2rx {
  d: path("M10.25 11v-1a1.75 1.75 0 0 1 3.5 0v1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qutlwjb1x {
  width: 6px;
  height: 4.75px;
  x: 9px;
  y: 11px;
  rx: 1px;
}

</style>
