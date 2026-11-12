<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vdsubobiu"/><path class="ijwbgek4s"/><path class="q9pwgx9_k"/><path class="w1fn0ab-e"/><path class="h60l1mbyb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:scanner-broken" /></template>
<style>
.h60l1mbyb {
  d: path("M12 12H22M2 12H8");
}

.ijwbgek4s {
  d: path("M22 15C22 18.7712 22 19.6569 20.8284 20.8284C19.6569 22 17.7712 22 14 22");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q9pwgx9_k {
  d: path("M22 9C22 5.22876 22 4.34315 20.8284 3.17157C20.1752 2.51839 19.3001 2.22937 18 2.10149M14 2C14.3492 2 14.6822 2 15 2.00093");
}

.vdsubobiu {
  d: path("M2 15C2 18.7712 2 19.6569 3.17157 20.8284C3.82475 21.4816 4.69989 21.7706 6 21.8985M10 22C9.65081 22 9.31779 22 9 21.9991");
}

.w1fn0ab-e {
  d: path("M10 2C6.22876 2 4.34315 2 3.17157 3.17157C2 4.34315 2 5.22876 2 9");
}

</style>
