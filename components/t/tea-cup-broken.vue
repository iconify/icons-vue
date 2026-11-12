<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ps0d2xk2r"/><path class="winbtub7u"/><path class="t0h-rybuv"/><path class="vt66uhuda"/><path class="pb4cfin7z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tea-cup-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pb4cfin7z {
  stroke-linejoin: round;
  d: path("M14.5002 7.5L14.6163 7.38388C15.1235 6.87671 15.1805 6.0738 14.7502 5.5C14.3198 4.9262 14.3769 4.12329 14.8841 3.61612L15.0002 3.5");
}

.ps0d2xk2r {
  d: path("M2.71598 16.1258C2.89681 17.6729 3.72352 19.0714 4.99182 19.9757C5.9263 20.6419 7.04537 21 8.19303 21H11.8069C12.9546 21 14.0736 20.6419 15.0081 19.9757C16.2764 19.0714 17.1031 17.6729 17.284 16.1258L17.6846 12.6978C17.7346 12.2706 17.7595 12.057 17.749 11.8809C17.694 10.9577 17.0132 10.1928 16.1027 10.0309C15.929 10 15.7139 10 15.2838 10H4.71612C4.286 10 4.07094 10 3.89725 10.0309C2.98677 10.1928 2.30599 10.9577 2.2509 11.8809C2.2404 12.057 2.26536 12.2706 2.3153 12.6978");
}

.t0h-rybuv {
  stroke-linejoin: round;
  d: path("M10.0002 2C9.44787 2.55228 9.44787 3.44772 10.0002 4C10.5524 4.55228 10.5524 5.44772 10.0002 6");
}

.vt66uhuda {
  stroke-linejoin: round;
  d: path("M5.00018 7.5L5.1163 7.38388C5.62347 6.87671 5.68053 6.0738 5.25018 5.5C4.81983 4.9262 4.8769 4.12329 5.38407 3.61612L5.50018 3.5");
}

.winbtub7u {
  d: path("M17.1093 17H19.0001C20.657 17 22.0001 15.6569 22.0001 14C22.0001 12.3431 20.657 11 19.0001 11H17.4848");
}

</style>
