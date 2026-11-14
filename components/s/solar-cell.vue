<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwwv9-38f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:solar-cell" /></template>
<style>
.mwwv9-38f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.39 17H5.32q-.101 0-.202-.012q-.1-.011-.199-.034t-.194-.058q-.095-.034-.186-.08q-.09-.045-.175-.1t-.163-.12t-.148-.138t-.13-.154t-.113-.168q-.051-.088-.092-.18q-.041-.093-.07-.19q-.03-.096-.049-.196q-.018-.099-.025-.201q-.007-.101-.002-.202q.004-.101.021-.201q.016-.1.044-.197l3-10.5q.039-.136.099-.264q.061-.129.141-.245q.08-.117.178-.22q.098-.102.211-.187t.239-.152q.125-.066.259-.111q.135-.045.274-.067Q8.178 3 8.32 3h10.36q.101 0 .202.012q.1.011.199.034t.194.058q.095.034.186.08q.09.045.175.1t.163.12t.148.138q.069.073.13.154t.113.168q.051.088.092.18q.041.093.07.19q.03.096.049.196q.018.099.025.201q.007.101.002.202q-.004.101-.021.201q-.016.1-.044.197l-1.736 6.074M5 10h14m-5-7l-4 14m6 1a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2-2v-2m0 6v2m-2-4h-2m6 0h2m-5.5-1.5l-1.25-1.25m4.25 4.25l1.25 1.25M19.5 16.5l1.25-1.25M16.5 19.5l-1.25 1.25");
}

</style>
