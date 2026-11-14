<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgawplbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sun-hat" /></template>
<style>
.fgawplbji {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.466 9.473Q6.459 4.25 12 4.25t6.534 5.223q-.106-.107-.245-.165T18 9.25H6q-.15 0-.289.058t-.245.165m-.209.423Q1.75 10.806 1.75 13q0 1.792 3.307 2.837q2.892.913 6.943.913q10.25 0 10.25-3.75q0-2.194-3.507-3.104q.007.052.007.104q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H6q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T5.25 10q0-.052.007-.104");
}

</style>
