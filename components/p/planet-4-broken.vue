<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i7e3qqbpl"/><path class="htrlefb5e"/><path class="t87r-6f3e"/><circle class="bia4v_qno"/><ellipse transform="rotate(-30 18.665 4.768)" class="r1zr_yb0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:planet-4-broken" /></template>
<style>
.bia4v_qno {
  cx: 18.665px;
  cy: 4.768px;
  r: 2.001px;
}

.htrlefb5e {
  d: path("M2.6947 10.7343C2.80203 10.8343 2.9046 10.925 3.00005 11.0052C3.00005 11.0052 5.28452 13 8.78452 13C11.1667 13 12.4311 11.818 13.5001 11.5039C15.509 10.9135 17.0001 11.0052 17.0001 11.0052C17.1279 11.0075 17.2707 11.011 17.4251 11.0156");
}

.i7e3qqbpl {
  d: path("M6 20.9297C7.17669 21.6104 8.54285 22 10 22C13.6301 22 16.6956 19.5821 17.6737 16.2689C17.886 15.5496 18 14.7881 18 14C18 12.9452 17.7959 11.9381 17.4249 11.016C16.2421 8.07568 13.3635 6 10 6C6.74483 6 3.94375 7.94416 2.69456 10.7347C2.24822 11.7318 2 12.8369 2 14C2 14.6986 2.08954 15.3763 2.25778 16.0222C2.44046 16.7235 2.71591 17.3874 3.07026 18");
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

.t87r-6f3e {
  d: path("M2.25768 16.0219C2.56575 16.0064 2.81573 16.002 2.99994 16.0051C2.99994 16.0051 4.6006 15.9135 6.75717 16.5038C7.90465 16.8179 9.26199 18 11.8193 18C14.1271 18 15.9427 17.2473 16.9999 16.6667C17.1998 16.5567 17.4285 16.4226 17.6736 16.2687");
}

</style>
