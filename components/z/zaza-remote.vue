<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="srgqwvbyw"/><circle class="ir3v99qlm"/><circle class="g1wzdfohm"/><circle class="t60208bfi"/><circle class="tapshyphd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zaza-remote" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g1wzdfohm {
  cx: 24px;
  cy: 40px;
  r: 0.75px;
  fill: currentColor;
}

.ir3v99qlm {
  cx: 8px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
}

.srgqwvbyw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.404 21.28zc1.013 0 1.835.806 1.835 1.8v1.832c0 .994-.822 1.8-1.835 1.8s-1.834-.806-1.834-1.8V23.08c0-.994.821-1.799 1.834-1.799m4.05.008v5.431m0-1.892l2.976-3.521m0 5.413l-2.277-2.715");
}

.t60208bfi {
  cx: 40px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
}

.tapshyphd {
  cx: 24px;
  cy: 8px;
  r: 0.75px;
  fill: currentColor;
}

</style>
