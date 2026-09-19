<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l1ls3ebcy"/><circle class="p99_eu-ao"/><circle class="k0ws9v69l"/><circle class="cx-_9ry5e"/><circle class="rhn-lyb0u"/><ellipse transform="rotate(-4.12 17.614 17.7)" class="yiio32b7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:plus-home-store" /></template>
<style>
.cx-_9ry5e {
  cx: 34.458px;
  cy: 27.785px;
  r: 2.86px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k0ws9v69l {
  cx: 27.533px;
  cy: 32.327px;
  r: 2.86px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l1ls3ebcy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.598 16.514c0 3.224 3.224 2.972 3.224 4.654s-7.345 1.346-7.345 7.514s5.635 9.393 13.514 9.393s20.663-3.449 20.663-14.776s-13.177-12.673-17.551-12.673s-12.505 1.654-12.505 5.888");
}

.p99_eu-ao {
  cx: 19.149px;
  cy: 33.196px;
  r: 2.86px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rhn-lyb0u {
  cx: 34.794px;
  cy: 19.991px;
  r: 2.86px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yiio32b7e {
  cx: 17.614px;
  cy: 17.7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.249px;
  ry: 1.682px;
}

</style>
