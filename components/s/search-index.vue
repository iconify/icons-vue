<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a-dcq_bkk"/><path class="cmlzals4a"/><path class="s44dnmlfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:search-index" /></template>
<style>
.a-dcq_bkk {
  d: path("M3.5 5.5a7.5 2.75 0 1 0 15 0a7.5 2.75 0 1 0-15 0");
}

.cmlzals4a {
  d: path("M3.5 5.5V18q0 .068.009.135t.027.135t.045.134t.063.132t.081.132t.098.13q.053.065.115.128q.062.064.133.126q.07.063.149.124t.166.12q.086.06.181.118t.197.114t.212.11t.226.107t.241.102t.254.098q.13.047.266.093q.137.045.279.088t.29.083t.301.078q.153.037.311.072t.321.066q.162.032.328.061q.167.029.337.055t.343.048q.174.023.35.043t.355.036t.359.029t.363.023t.365.017t.367.01t.368.003q.447 0 .891-.019m6.609-9.895V5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s44dnmlfn {
  d: path("M3.5 11.75q0 .068.009.135t.027.135t.045.134t.063.132q.036.067.081.132q.045.066.098.13q.053.065.115.128q.062.064.133.126q.07.063.149.124t.166.12q.086.06.181.118t.197.114t.212.11t.226.107q.117.052.241.102t.254.098t.266.093q.137.045.279.088t.29.083t.301.078t.311.072t.321.066t.328.061q.167.029.337.055t.343.048t.35.043q.176.019.355.036q.178.016.359.029q.18.013.363.023q.182.01.365.017q.183.006.367.01q.184.003.368.003l.181-.001M13.5 17a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m6 2.5L22 22");
}

</style>
