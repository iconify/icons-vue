<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p9cs3lbuu"/><path class="tw9en851n"/><path class="a68-958_y"/><path class="gh_qd2oso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:reskilling" /></template>
<style>
.a68-958_y {
  d: path("M18.75 9.25L20.5 11L22 9.25M11 20.5c-4.5 0-7.5-3-7.5-7.5");
}

.gh_qd2oso {
  d: path("M2 14.75L3.5 13l1.75 1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p9cs3lbuu {
  d: path("M4.974 2.852a3 3 0 1 1-2.122 2.122");
}

.tw9en851n {
  d: path("m4.75 2.75l1 3l-3-1m5 3l2.75 2.75m3 3L16 16m2.854-.768l1.414 1.414a1.5 1.5 0 0 1 0 2.122a1.5 1.5 0 0 1-2.122 0l-1.414-1.414a1.5 1.5 0 0 1 0-2.122a1.5 1.5 0 0 1 2.122 0M13 3.5c4.5 0 7.5 3 7.5 7.5");
}

</style>
