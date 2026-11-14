<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wvcmcfazo"/><path class="gcui2yj9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rear-window" /></template>
<style>
.gcui2yj9s {
  d: path("M7.25 13.25a5.5 5.5 0 0 1 9.5 0M12 16h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wvcmcfazo {
  d: path("M9.233 5h5.534a3.5 3.5 0 0 1 3.396 2.651l1.75 7A3.5 3.5 0 0 1 16.517 19H7.483a3.5 3.5 0 0 1-3.396-4.349l1.75-7A3.5 3.5 0 0 1 9.233 5");
}

</style>
