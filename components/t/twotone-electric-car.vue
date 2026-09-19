<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d25qxabhq"/><path class="j2mtpvbxm"/><circle class="l1tdjlb-d"/><circle class="a111kcbov"/><path class="q6g819tak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-electric-car" /></template>
<style>
.a111kcbov {
  cx: 16.5px;
  cy: 10.5px;
  r: 1.5px;
  fill: currentColor;
}

.d25qxabhq {
  fill: currentColor;
  d: path("M5 13h14V8H5zm11.5-4c.83 0 1.5.67 1.5 1.5s-.67 1.5-1.5 1.5s-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5m-9 0c.83 0 1.5.67 1.5 1.5S8.33 12 7.5 12S6 11.33 6 10.5S6.67 9 7.5 9");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.j2mtpvbxm {
  fill: currentColor;
  d: path("M18.92 2.01C18.72 1.42 18.16 1 17.5 1h-11c-.66 0-1.21.42-1.42 1.01L3 8v8c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-1h12v1c0 .55.45 1 1 1h1c.55 0 1-.45 1-1V8zM6.85 3h10.29l1.08 3.11H5.77zM19 13H5V8h14z");
}

.l1tdjlb-d {
  cx: 7.5px;
  cy: 10.5px;
  r: 1.5px;
  fill: currentColor;
}

.q6g819tak {
  fill: currentColor;
  d: path("M7 20h4v-2l6 3h-4v2z");
}

</style>
