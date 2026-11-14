<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yq_fk8bkn"/><path class="pmia1dbdq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:printer-low-ink" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pmia1dbdq {
  d: path("M12 6.75S10.5 8.5 10.5 9.5a1.5 1.5 0 0 0 3 0c0-1-1.5-2.75-1.5-2.75");
}

.yq_fk8bkn {
  d: path("M6.875 4h10.25A4.375 4.375 0 0 1 21.5 8.375v1.75a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 10.125v-1.75A4.375 4.375 0 0 1 6.875 4M6.5 14.5v5a1 1 0 0 0 1 1h9a1 1 0 0 0 1-1v-5m-8 3h5");
}

</style>
