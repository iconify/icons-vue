<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="degntu5_g"/><path class="f_-h6bcte"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:privacy-ai" /></template>
<style>
.degntu5_g {
  d: path("M14.692 18.602A9.2 9.2 0 0 1 12 19c-4 0-7.5-2.5-9.5-7c.584-1.314 1.296-2.457 2.11-3.418m4.741-3.197A9.2 9.2 0 0 1 12 5c4 0 7.5 2.5 9.5 7c-.593 1.334-1.317 2.492-2.147 3.461");
}

.f_-h6bcte {
  d: path("M8.532 12.473q.019.142.05.282t.074.277q.042.138.096.271q.053.133.117.261q.064.129.139.252q.074.122.158.238q.085.117.178.226q.094.108.196.209t.212.193t.227.176t.241.155q.123.073.253.136q.129.063.263.115q.133.051.271.092t.278.07t.283.047m3.902-3.931q-.019-.142-.049-.283t-.072-.277q-.042-.138-.095-.271q-.053-.134-.117-.262q-.063-.129-.137-.252t-.158-.24t-.177-.225q-.093-.11-.194-.211t-.212-.194q-.109-.093-.226-.176t-.24-.157t-.252-.137t-.263-.115q-.133-.053-.271-.094q-.137-.041-.278-.071q-.14-.03-.283-.048M3.5 3.5l17 17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
