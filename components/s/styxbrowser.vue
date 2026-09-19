<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="m_6h9kb1s"><path class="s0x-ynbed"/><path class="dhrcrsy9u"/><path class="vfrf3rb8m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:styxbrowser" /></template>
<style>
.dhrcrsy9u {
  d: path("M34.4 9.1c9.1-5.9 12-4.2 6.5 3.8S23.5 32.4 14.4 38.3s-12 4.2-6.5-3.8");
}

.m_6h9kb1s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 90;
}

.s0x-ynbed {
  d: path("M23.1 5.5c10.2 0 18.5 8.3 18.5 18.5s-8.3 18.5-18.5 18.5S4.6 34.2 4.6 24S12.9 5.5 23.1 5.5");
}

.vfrf3rb8m {
  d: path("m4.8 26.5l3-4.3l4.2-.9l3.1 1.9l2 3l.9 2.9l4 1.1m-9.9-16c1.4 0 2.5 1.1 2.5 2.5s-1.1 2.5-2.5 2.5s-2.5-1.1-2.5-2.5s1.1-2.5 2.5-2.5m23.5 8.1H37l1.9-1.7l1.5-3.3m-12 7.6c-1.5.1-2.9-1-3-2.6c-.1-1.5 1-2.9 2.6-3c1.5-.1 2.9 1 3 2.6v.4m3.3 16.4L33 35.4l-1.8-.3l.2-2.3l4.8-3.2l4.8-.5M19.8 5.8v5.5l2.2 3l3.8 1.8l2.9-1.4l2.9 1.1l1.1 2.3l.3 1.7m-7.7 12.9l.6 2.4l-1.7 2.6l-4 1.8l-5.7.9");
}

</style>
