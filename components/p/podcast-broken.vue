<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="z4w5lob6d"/><path class="lh43htbqq"/><path class="unm252b3m"/><path class="k6v9g8zhf"/><path class="vjikwlb8p"/><path class="fsvva1laf"/><path class="ip0k8xrgf"/><path class="ezhx_r9yu"/><path class="n30k0z4xd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:podcast-broken" /></template>
<style>
.ezhx_r9yu {
  d: path("M18 12C18 10.8954 18.8954 10 20 10C21.1046 10 22 10.8954 22 12V14C22 15.1046 21.1046 16 20 16C18.8954 16 18 15.1046 18 14V12Z");
}

.fsvva1laf {
  d: path("M18.0004 14.1538C18.0004 15.1734 18.827 16 19.8466 16M4.1543 16C5.1739 16 6.00045 15.1734 6.00045 14.1538V9.99998C6.00045 6.68628 8.68673 4 12.0004 4C14.6129 4 16.8353 5.66962 17.659 8");
}

.ip0k8xrgf {
  d: path("M2 12C2 10.8954 2.89543 10 4 10C5.10457 10 6 10.8954 6 12V14C6 15.1046 5.10457 16 4 16C2.89543 16 2 15.1046 2 14V12Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k6v9g8zhf {
  d: path("M9 10L10 10");
}

.lh43htbqq {
  d: path("M13 10L15 10");
}

.n30k0z4xd {
  d: path("M12 16V19");
}

.unm252b3m {
  d: path("M13 13L15 13");
}

.vjikwlb8p {
  d: path("M9 13L10 13");
}

.z4w5lob6d {
  d: path("M9 10C9 8.34315 10.3431 7 12 7C13.6569 7 15 8.34315 15 10V13C15 14.6569 13.6569 16 12 16C10.3431 16 9 14.6569 9 13V10Z");
}

</style>
