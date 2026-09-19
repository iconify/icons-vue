<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zw9jrubtm"/><circle class="ip0rdvb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vivint" /></template>
<style>
.ip0rdvb2p {
  cx: 39.18px;
  cy: 35.12px;
  r: 4.32px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zw9jrubtm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.55 8.83l-12 10.92a3.24 3.24 0 0 0-1.06 2.4v16.22a1.08 1.08 0 0 0 1.08 1.08H31a1.08 1.08 0 0 0 1.08-1.08V22.15a3.24 3.24 0 0 0-1.08-2.4L19 8.83a1.09 1.09 0 0 0-1.45 0");
}

</style>
