<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mf7bm9f0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mortgage-product-transfer" /></template>
<style>
.mf7bm9f0i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.5 16.5l12-12M4 6.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m12.696 6.805q-.081-.148-.18-.283t-.215-.256q-.117-.121-.248-.225q-.132-.105-.276-.19t-.299-.152q-.154-.065-.316-.11q-.162-.044-.328-.067Q14.668 12 14.5 12q-.123 0-.245.012t-.243.036q-.12.024-.238.06t-.231.082q-.113.047-.221.105q-.109.058-.211.126q-.102.069-.197.146q-.095.078-.182.165t-.165.182t-.146.197t-.126.211t-.105.221q-.047.114-.082.231t-.06.238q-.024.121-.036.243T12 14.5q0 .301.071.593q.072.292.21.559M15 16.25h6m-1.75-1.75L21 16.25m0 3.5h-6m1.75 1.75L15 19.75");
}

</style>
