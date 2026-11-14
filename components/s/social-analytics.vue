<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g_km8xb1y"/><path class="st8btfbcn"/><path class="st8bpl8_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:social-analytics" /></template>
<style>
.g_km8xb1y {
  d: path("M11.935 17H6.25V9.25l3-5.5c1-1.25 3-.75 2.75 1L11.75 8H16q.094-.001.188.008t.187.029q.092.019.182.048t.176.068t.168.086t.157.103q.076.057.145.121q.07.063.132.135q.062.071.116.148t.1.16t.082.17t.063.177t.044.184t.023.187t.004.188q-.004.095-.017.188l-.565 3.109M3.75 9zA1.25 1.25 0 0 1 5 10.25v5.5A1.25 1.25 0 0 1 3.75 17a1.25 1.25 0 0 1-1.25-1.25v-5.5A1.25 1.25 0 0 1 3.75 9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.st8bpl8_q {
  d: path("m16.75 19l1.5-2.25L19.5 18l2-2.75");
}

.st8btfbcn {
  d: path("M14.75 14.5v6.75h6.75");
}

</style>
