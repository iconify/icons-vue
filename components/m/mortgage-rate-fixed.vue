<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4miuzb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mortgage-rate-fixed" /></template>
<style>
.e4miuzb6q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.5 16.5l12-12M4 6.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm12.163 6.134q-.17-.152-.365-.271q-.195-.118-.408-.199t-.438-.123Q14.728 12 14.5 12q-.123 0-.245.012t-.243.036q-.12.024-.238.06t-.231.082q-.113.047-.221.105q-.109.058-.211.126q-.102.069-.197.146q-.095.078-.182.165t-.165.182t-.146.197t-.126.211t-.105.221q-.047.114-.082.231t-.06.238q-.024.121-.036.243T12 14.5q0 .555.235 1.058M15 17.5h6v4h-6Zm1.5 0v-1a1.5 1.5 0 0 1 3 0v1");
}

</style>
