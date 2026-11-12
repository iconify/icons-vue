<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nakcxna2k"/><path class="tt1o2hb5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:radar-2-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nakcxna2k {
  d: path("M11.9996 12L5.00148 6.33594C4.57236 5.98862 3.93821 6.05231 3.6355 6.51399C3.06629 7.38212 2.62364 8.35437 2.34029 9.41185C0.910876 14.7465 4.0767 20.2299 9.41136 21.6593C14.746 23.0887 20.2294 19.9229 21.6588 14.5882C23.0882 9.25357 19.9224 3.7702 14.5877 2.34078C11.9552 1.63538 9.28636 2.04906 7.08641 3.29021");
}

.tt1o2hb5m {
  d: path("M7.36914 8.18461C6.51379 9.2216 6 10.5508 6 12C6 15.3137 8.68629 18 12 18C15.3137 18 18 15.3137 18 12C18 8.68629 15.3137 6 12 6C11.337 6 10.6991 6.10754 10.1028 6.30613");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
