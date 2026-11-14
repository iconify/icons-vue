<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtjjqpkrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:serverless-security" /></template>
<style>
.dtjjqpkrz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 2.75h3q.107 0 .21.03t.194.088q.09.057.16.138t.116.178l5.733 12.349q.121-.151.299-.225l3-1.25Q17.85 14 18 14t.288.058l3 1.25q.103.042.189.113q.085.071.147.163t.094.199t.032.217v2.25q0 2.709-3.455 4.189q-.141.061-.295.061t-.295-.061q-3.455-1.48-3.455-4.189v-.043l-.008-.003q-.14-.051-.25-.152t-.172-.236l-3.177-6.843l-5.295 6.98q-.045.059-.1.108t-.119.086q-.064.038-.134.062t-.143.034t-.147.006q-.074-.005-.145-.023q-.072-.019-.138-.052q-.066-.032-.125-.076q-.119-.091-.194-.219q-.076-.129-.096-.277t.017-.292t.128-.263l5.5-7.25q.13-.171.33-.247l-2.461-5.3H5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T4.25 3.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q4.926 2.75 5 2.75");
}

</style>
