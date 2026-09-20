<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="aj5u4vpba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yego" /></template>
<style>
.aj5u4vpba {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.05 20l-2.6 4l-2.6-4m2.6 8v-4m6.067 0h2.7m1.3 4h-4v-8h4m14.933 8zc-1.5 0-2.6-1.2-2.6-2.6v-2.7c0-1.5 1.2-2.7 2.6-2.7c1.5 0 2.7 1.2 2.7 2.7v2.6c0 1.5-1.2 2.7-2.7 2.7m-6.067-5.3c0-1.5-1.2-2.7-2.7-2.7s-2.7 1.2-2.7 2.7v2.7c0 1.5 1.2 2.6 2.7 2.6s2.7-1.2 2.7-2.6h-2.7");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
