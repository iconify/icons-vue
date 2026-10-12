<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="myxzkqb-h"/><circle class="uxwtxcbyr"/><circle class="bhnvrvjtt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:suv" /></template>
<style>
.bhnvrvjtt {
  cx: 17px;
  cy: 16px;
  r: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.myxzkqb-h {
  d: path("M2.75 15v-3.25a1.5 1.5 0 0 1 1.2-1.47l1.8-.36l1.8-3.06a2 2 0 0 1 1.72-1.11h9.03a2 2 0 0 1 1.92 1.44l.95 3.26a2 2 0 0 1 .08.56V15a1 1 0 0 1-1 1H3.75a1 1 0 0 1-1-1m3-4.75h15.5m-8-4.5v4.5");
}

.uxwtxcbyr {
  cx: 7px;
  cy: 16px;
  r: 2.5px;
}

</style>
