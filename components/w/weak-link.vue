<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b15nx58lo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:weak-link" /></template>
<style>
.b15nx58lo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 9H9a3 3 0 0 1 3 3a3 3 0 0 1-3 3H5.5a3 3 0 0 1-3-3a3 3 0 0 1 3-3m13.378.024q.134.017.267.046q.132.029.261.07t.254.093q.125.053.245.116q.12.064.233.138t.22.158t.205.177t.188.195q.089.101.17.211q.08.109.149.225q.07.116.129.238q.06.122.107.249q.048.127.085.257q.036.131.06.264q.025.134.037.269q.012.134.012.27q0 .311-.064.615q-.063.304-.188.589q-.125.284-.305.537t-.409.464m-5.927.769q-.134-.017-.265-.047q-.132-.03-.261-.071q-.128-.041-.253-.094q-.124-.053-.243-.117q-.119-.063-.232-.137t-.219-.159t-.203-.177t-.187-.194t-.168-.211q-.08-.109-.149-.225q-.07-.116-.129-.238t-.106-.248t-.083-.256t-.061-.263q-.024-.133-.036-.267Q12 12.135 12 12q0-.272.049-.539q.049-.268.145-.522q.096-.255.236-.487q.141-.233.321-.437M17 5.5l-1.5 5L18 13l-1.5 5.5");
}

</style>
