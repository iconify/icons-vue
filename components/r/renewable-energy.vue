<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fb9vxbc2r"/><circle class="ons53cb4g"/><path class="qku5pibwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:renewable-energy" /></template>
<style>
.fb9vxbc2r {
  d: path("M4.01 9.09a8.5 8.5 0 0 1 15.98 0m-2.26-1.06l2.26 1.06l1.06-2.26m-1.06 8.08a8.5 8.5 0 0 1-15.98 0m2.26 1.06l-2.26-1.06l-1.06 2.26");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ons53cb4g {
  cx: 12px;
  cy: 12px;
  r: 2.5px;
}

.qku5pibwd {
  d: path("M12 6.5v.75m0 9.5v.75M6.5 12h.75m9.5 0h.75");
}

</style>
