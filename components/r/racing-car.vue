<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qmgxshajg"/><path class="xitdx630u"/><path class="hbgrd3bms"/><path class="s94haibmq"/><path class="ei6z22b9g"/><circle class="estzncb_v"/><circle class="bkwqtac9s"/><circle class="vrpby8a8s"/><circle class="v_s2l3bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:racing-car" /></template>
<style>
.bkwqtac9s {
  cx: 26.67px;
  cy: 111.33px;
  r: 8.44px;
  fill: var(--svg-color--78a3ad, #78a3ad);
}

.ei6z22b9g {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M128 88.11h-10.56l2.12-4.22H128zm0 8.45h-10.56l2.12-4.23H128zm0 8.44h-10.56l2.12-4.22H128z");
}

.estzncb_v {
  cx: 26.67px;
  cy: 111.33px;
  r: 12.67px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.hbgrd3bms {
  fill: var(--svg-color--ed6c30, #ed6c30);
  d: path("M86.67 90.22c-2.04 0-4.45 1.49-5.36 3.31l-3.02 6.04c-.91 1.82-3.33 3.31-5.36 3.31H55c-2.04 0-3.71-1.67-3.71-3.71v-3.14c0-2.04-1.58-3.18-3.52-2.54L1.91 111.73c-2.85 1.59-1.73 5.93 1.54 5.93H105.3c2.04 0 3.01-1.51 2.15-3.36l-9.56-20.71c-.85-1.85-3.22-3.36-5.26-3.36h-5.96z");
}

.qmgxshajg {
  fill: none;
  stroke: var(--svg-color--2f2f2f, #2f2f2f);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--3px, 3px);
  d: path("m52 109.22l4.22-10.55");
}

.s94haibmq {
  fill: var(--svg-color--ed6c30, #ed6c30);
  d: path("M128 83.18c0-1.93-1.58-3.51-3.51-3.51h-7.76c-1.93 0-4.13 1.45-4.89 3.23l-9.9 23.1c-.76 1.77.2 3.23 2.13 3.23h20.42c1.93 0 3.51-1.58 3.51-3.51z");
}

.v_s2l3bdd {
  cx: 102.67px;
  cy: 111.33px;
  r: 8.44px;
  fill: var(--svg-color--78a3ad, #78a3ad);
}

.vrpby8a8s {
  cx: 102.67px;
  cy: 111.33px;
  r: 12.67px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.xitdx630u {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M74.52 109.22a2.102 2.102 0 0 1-1.88-3.05L83.2 85.06a2.1 2.1 0 0 1 2.83-.94c1.04.52 1.47 1.79.94 2.83l-10.56 21.11c-.37.74-1.12 1.16-1.89 1.16");
}

</style>
