<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7c8librf"/><path class="zo7qtulrh"/><circle class="i41e6pm1x"/><circle class="icc3mmbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-directions-car" /></template>
<style>
.i41e6pm1x {
  cx: 7.5px;
  cy: 14.5px;
  r: 1.5px;
  fill: currentColor;
}

.icc3mmbjf {
  cx: 16.5px;
  cy: 14.5px;
  r: 1.5px;
  fill: currentColor;
}

.m7c8librf {
  fill: currentColor;
  d: path("M5 17h14v-5H5zm11.5-4c.83 0 1.5.67 1.5 1.5s-.67 1.5-1.5 1.5s-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5m-9 0c.83 0 1.5.67 1.5 1.5S8.33 16 7.5 16S6 15.33 6 14.5S6.67 13 7.5 13");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.zo7qtulrh {
  fill: currentColor;
  d: path("M18.92 6.01C18.72 5.42 18.16 5 17.5 5h-11c-.66 0-1.21.42-1.42 1.01L3 12v8c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-1h12v1c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-8zM6.85 7h10.29l1.08 3.11H5.77zM19 17H5v-5h14z");
}

</style>
