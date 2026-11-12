<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="x0fuh28ql"/><path class="r2hba1b6t"/><path class="t87r-6f3e"/><circle class="bia4v_qno"/><ellipse transform="rotate(-30 18.665 4.768)" class="r1zr_yb0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:planet-4-linear" /></template>
<style>
.bia4v_qno {
  cx: 18.665px;
  cy: 4.768px;
  r: 2.001px;
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r1zr_yb0c {
  cx: 18.665px;
  cy: 4.768px;
  rx: 2.506px;
  ry: 0.472px;
}

.r2hba1b6t {
  d: path("M2.69458 10.7344C2.8019 10.8344 2.90448 10.925 2.99993 11.0052C2.99993 11.0052 5.28439 13.0001 8.78439 13.0001C11.1666 13.0001 12.431 11.818 13.4999 11.5039C15.5089 10.9136 16.9999 11.0052 16.9999 11.0052C17.1278 11.0076 17.2706 11.011 17.4249 11.0157");
}

.t87r-6f3e {
  d: path("M2.25768 16.0219C2.56575 16.0064 2.81573 16.002 2.99994 16.0051C2.99994 16.0051 4.6006 15.9135 6.75717 16.5038C7.90465 16.8179 9.26199 18 11.8193 18C14.1271 18 15.9427 17.2473 16.9999 16.6667C17.1998 16.5567 17.4285 16.4226 17.6736 16.2687");
}

.x0fuh28ql {
  d: path("M18 14C18 18.4183 14.4183 22 10 22C5.58172 22 2 18.4183 2 14C2 9.58172 5.58172 6 10 6C14.4183 6 18 9.58172 18 14Z");
}

</style>
