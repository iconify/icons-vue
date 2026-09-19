<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="dv_-0ibig"/><circle class="xg1ei1bsr"/><path class="wxe0f7bfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-departure-board" /></template>
<style>
.dv_-0ibig {
  cx: 5.5px;
  cy: 16.5px;
  r: 1.5px;
  fill: currentColor;
}

.wxe0f7bfr {
  fill: currentColor;
  d: path("M16 1a6.98 6.98 0 0 0-5.75 3.02C9.84 4.01 9.43 4 9 4c-4.42 0-8 .5-8 4v10c0 .88.39 1.67 1 2.22V22c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-1h8v1c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-1.78c.61-.55 1-1.34 1-2.22v-3.08c3.39-.49 6-3.39 6-6.92c0-3.87-3.13-7-7-7M9 6h.29c-.09.32-.16.66-.21.99H3.34C3.89 6.46 5.31 6 9 6M3 8.99h6.08c.16 1.11.57 2.13 1.18 3.01H3zM15 18c0 .37-.21.62-.34.73l-.29.27H3.63l-.29-.27A.97.97 0 0 1 3 18v-4h9.41c.78.47 1.65.79 2.59.92zm1-5c-2.76 0-5-2.24-5-5s2.24-5 5-5s5 2.24 5 5s-2.24 5-5 5m.5-9H15v5l3.62 2.16l.75-1.23l-2.87-1.68z");
}

.xg1ei1bsr {
  cx: 12.5px;
  cy: 16.5px;
  r: 1.5px;
  fill: currentColor;
}

</style>
