<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="q1m2erv2p"/><path class="jpqkjkhus"/><ellipse class="hg8187bsc"/><ellipse class="q-4sqnh6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:slightly-frowning-face" /></template>
<style>
.hg8187bsc {
  cx: 12px;
  cy: 13.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 3.5px;
}

.jpqkjkhus {
  fill: var(--svg-color--664500, #664500);
  d: path("M25.485 27.379C25.44 27.2 24.317 23 18 23s-7.44 4.2-7.485 4.379a.5.5 0 0 0 .237.554a.505.505 0 0 0 .6-.077C11.371 27.837 13.306 26 18 26s6.63 1.837 6.648 1.855a.5.5 0 0 0 .598.081a.5.5 0 0 0 .239-.557");
}

.q-4sqnh6r {
  cx: 24px;
  cy: 13.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 3.5px;
}

.q1m2erv2p {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

</style>
